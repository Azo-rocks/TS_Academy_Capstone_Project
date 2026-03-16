# TS Academy Capstone Project: Time Series Forecasting of Truck Sales

## Project Overview
This project was completed as part of the TS Academy Data Science Capstone Project.

The objective of this analysis is to forecast truck sales using time series modeling techniques. The project follows a complete workflow including data preprocessing, exploratory data analysis, decomposition, stationarity testing, differencing, model building, forecasting, and evaluation.

## Problem Statement
Truck sales data changes over time and may contain trends and seasonal patterns. The goal of this project is to analyze historical truck sales data and build a forecasting model that can predict future sales as accurately as possible.

## Dataset
The dataset used in this project is a truck sales dataset containing time-based sales records.

Main variables include:

- **Month** – date of observation
- **Sales** – number of truck units sold

The dataset is suitable for time series analysis because observations are recorded sequentially over time.

**File included in this repository:**
- `Truck_sales_033633.csv`

## Project Workflow
The notebook covers the following stages:

1. Data loading and preprocessing  
2. Exploratory data analysis  
3. Time series visualization  
4. Time series decomposition  
5. Stationarity testing using the Augmented Dickey-Fuller test  
6. Differencing transformation  
7. ACF and PACF analysis  
8. Train-test split  
9. SARIMA model building  
10. Forecasting and evaluation using RMSE and MAE  
11. Residual analysis and diagnostics  
12. Final conclusions and recommendations  

## Model

A **SARIMA model** was used to capture both trend and seasonal patterns in the truck sales data.

Evaluation metrics used:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

The model successfully captures the seasonal behavior in the data and produces reasonable forecasts.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Repository Contents
data/ → dataset used in analysis  
notebooks/ → Jupyter notebook containing the analysis  
images/ → visualization outputs  
README.md → project documentation  
requirements.txt → project dependencies

## Key Skills Demonstrated
- Time series analysis
- Data preprocessing
- Stationarity testing
- Seasonal decomposition
- SARIMA forecasting
- Forecast evaluation
- Residual diagnostics
- Data storytelling

## Author
AbdulAzeem Shorunke

## Note
This repository was created as part of my learning journey in Data Science and demonstrates my ability to carry out an end-to-end time series forecasting project using Python.
