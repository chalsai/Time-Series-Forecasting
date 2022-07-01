# Time-Series-Forecasting


# Project description

Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.

The RMSE metric on the test set should not be more than 48.

# Project instructions
Download the data and resample it by one hour.
Analyze the data.
Train different models with different hyperparameters. The test sample should be 10% of the initial dataset.
Test the data using the test sample and provide a conclusion.
Data set


● The data is stored in the taxi.csv (https://bit.ly/3p1QPAv) file. ○ Download or import the dataset from the URL. ● The number of orders is in the num_orders column.

# summary

we found that our model is non stationary, we built linear model and tree based model and found best result for tree based model and with rmse less than 41 which is enough. also we checked daily changes, week changes and found drift around 22-23 days
