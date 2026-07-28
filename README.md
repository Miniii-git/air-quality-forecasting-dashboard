# Air Quality Forecasting and Streamlit Dashboard
Time series analysis, forecasting, and Streamlit dashboard for PM10, PM2.5, and NO₂ air pollution data in Italy.

## Overview

This project analyzes and forecasts air pollutant concentrations at an Italian monitoring station using official data from the European Environment Agency.

The analysis focuses on three regulated pollutants:

* PM10
* PM2.5
* NO₂

The project combines data acquisition, exploratory data analysis, time series forecasting, model evaluation, and an interactive Streamlit dashboard. It also evaluates whether predicted pollution levels are expected to comply with the European Union air-quality limits for 2030.

## Project Objectives

* Retrieve and preprocess official European air-quality data
* Analyze data quality, missing observations, trends, seasonality, and outliers
* Compare multiple time series forecasting models
* Generate pollutant forecasts through 2030
* Evaluate expected compliance with EU air-quality targets
* Build an interactive dashboard for data exploration and decision support

## Data Source

The data was obtained from the European Environment Agency Air Quality Download Service using the `airbase` Python library.

The dataset contains validated measurements for the Italian monitoring station `IT1876A` from 2013 to 2024.

## Forecasting Models

The following forecasting approaches were evaluated:

* Seasonal Naive baseline
* Linear Trend with monthly seasonality
* Holt–Winters Exponential Smoothing
* SARIMA

Models were evaluated using a three-fold rolling-origin backtest with a 12-month forecasting horizon.

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Symmetric Mean Absolute Percentage Error (sMAPE)

## Dashboard

The Streamlit dashboard provides:

* Historical pollutant trends
* Data-quality and completeness analysis
* Pollutant comparison
* Interactive forecasting visualizations
* Forecasting model comparison
* Expected compliance with EU 2030 limits

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Statsmodels
* Streamlit
* Parquet
* Airbase API



## Screenshots

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/55c6cd61-2f5a-4031-9265-44a94354b8f8" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c8c94285-1bec-4a3d-9bcf-4acf94e04e62" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/acf85a91-d740-4e8d-864e-0c9f737a0d83" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/b8bc8729-4b9f-43f3-b38d-4a177bfc69de" />



