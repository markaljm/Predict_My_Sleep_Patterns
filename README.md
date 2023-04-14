# Predict_My_Sleep_Patterns
In this project, the goal is to predict daily sleep hours using a time series
In this project, the goal is to predict daily sleep hours using a time series dataset containing two columns: 'date' and 'sleep_hours'. The dataset is split into a training dataset and a testing dataset. The training dataset is used to train the model, and the testing dataset is used to evaluate the model's performance by calculating the Root Mean Squared Error (RMSE).

The Facebook Prophet library is utilized to create a time series forecasting model. Prophet is a powerful and flexible forecasting tool that automatically captures and fits the seasonal and trend components in the data. It works well with daily data and can handle missing values and outliers.

Initially, a basic Prophet model is fit to the training dataset, and future sleep hours are predicted for the dates in the testing dataset. The model's performance is evaluated using the RMSE, comparing the predicted sleep hours with the actual sleep hours in the test dataset.
