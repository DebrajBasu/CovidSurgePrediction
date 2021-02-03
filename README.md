# CovidSurgePrediction
The Covid patient surge prediction is critical to healthcare system to not overwhelm the resources and optimizes whenever required. In this exercise, we will deal with real covid data and build time-series forcasting models to predict a number in the future.

We have tested univariate scenario with the lag of each target used as input to the machine learning model
Since we cannot do 'normal' cross validation method to do hyperparameter tuning, we use nested walk forward validation to asses the performance of the ML algorithms.
In live scenario, we have used walk forward hyper-paramter optimization and then used that to retrained model to make future prediction.
Beside point prediction (forecast) we have used quantile loss function to define the 5% and 95% prediction intervals.
