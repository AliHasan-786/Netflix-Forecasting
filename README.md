# Netflix-Forecasting

## Overview
This project aims to analyze and forecast Netflix's subscription growth using time series analysis. The ARIMA model is applied to quarterly data to predict future subscriber counts, providing valuable insights into Netflix's growth trajectory.

## Dependencies
- Pandas
- Numpy
- Matplotlib
- Plotly
- Statsmodels

These Python libraries are essential for data manipulation, visualization, and applying the ARIMA model for time series forecasting.

## Data
The `Netflix-Subscriptions.csv` dataset contains historical data on Netflix's subscription counts at the start of each quarter from 2013 to 2023.

## Preprocessing
The data is processed by converting the 'Time Period' column into datetime format and calculating the quarterly and yearly growth rates. This step is crucial for the subsequent time series forecasting.

## Model Training and Evaluation
The ARIMA (AutoRegressive Integrated Moving Average) model is trained on the processed dataset. The model's adequacy is assessed by examining the ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) plots to select appropriate parameters.

## Usage
To replicate the forecast:
1. Install the required dependencies.
2. Run the provided code to preprocess the data and train the ARIMA model.
3. Evaluate the model's performance and generate forecasts.

## Results
The project outputs include:
- A visualization of Netflix's subscription growth over time.
- Bar graphs depicting quarterly and yearly growth rates.
- ACF and PACF plots to determine the ARIMA model parameters.
- Future subscription predictions visualized alongside historical data.

The analysis and forecast provide a comprehensive view of Netflix's performance and can aid strategic decision-making regarding customer growth.

