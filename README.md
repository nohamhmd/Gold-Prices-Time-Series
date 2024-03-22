# Gold-Prices-Time-Series
### Overview
This Jupyter Notebook demonstrates the process of time series analysis using the Autoregressive Integrated Moving Average (ARIMA) model. The analysis focuses on forecasting gold prices based on historical monthly data.

## Dependencies
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
statsmodels
scikit-learn

## Analysis Steps
Data Loading and Preprocessing: Read the historical gold prices data from the CSV file and preprocess the data.
Exploratory Data Analysis (EDA): Visualize the time series data to understand its characteristics and identify any trends, seasonality, or anomalies.
Stationarity Test: Conduct Augmented Dickey-Fuller (ADF) test to check the stationarity of the time series data.
Differencing: Perform differencing on the data to make it stationary.
Model Fitting: Fit an ARIMA model to the stationary data and interpret the model results.
Forecasting: Generate forecasts for future time periods using the fitted ARIMA model.
