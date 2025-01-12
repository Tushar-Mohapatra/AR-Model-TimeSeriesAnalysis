# Time Series Analysis (TSA) - Autoregressive (AR) Model

## Overview
This repository provides an implementation of the **Autoregressive (AR) Model** for Time Series Analysis. The AR model is a widely used statistical technique that represents a time series using its past values. The goal of this project is to help understand, model, and forecast time series data effectively.

## Features
- **AR Model Estimation:** Fit an autoregressive model to a given time series.
- **Model Diagnostics:** Evaluate the model's performance using residual analysis.
- **Forecasting:** Predict future values based on the fitted AR model.
- **Visualization:** Plot the original time series, fitted values, and forecasts.

## Requirements
The following libraries are required to run the project:
- Python 3.8+
- numpy
- pandas
- matplotlib
- statsmodels
- 
## Limitations
- Assumes the time series is stationary. Non-stationary data must be transformed before applying the AR model.
- Works best with univariate time series data.

## References
1. [Box, G. E., Jenkins, G. M., & Reinsel, G. C. (2015). Time Series Analysis: Forecasting and Control. Wiley.]
2. [Hamilton, J. D. (1994). Time Series Analysis. Princeton University Press.]
