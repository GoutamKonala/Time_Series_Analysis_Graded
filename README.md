# Time Series Analysis - AirPassengers Dataset

This repository contains a graded exercise on Time Series Analysis (TSA) applied to the classic AirPassengers dataset. The goal is to forecast the number of airline passengers using various statistical and machine learning models.

## Project Overview

In this exercise, we analyze historical passenger count data from an airline company to forecast future demand. This helps in optimizing budgeting and resource management.

## Dataset

The dataset used is `AirPassengers.csv`, which contains monthly totals of international airline passengers from 1949 to 1960.

- **Source**: Box & Jenkins (1976)
- **Time Period**: January 1949 - December 1960
- **Frequency**: Monthly
- **Columns**:
    - `Month`: The month of observation (YYYY-MM)
    - `Passengers`: Number of airline passengers

## Prerequisites

To run the notebook, you need the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- sklearn
- scipy

## Models Implemented

The following time series forecasting models are implemented and evaluated in the notebook:

1.  **Linear Regression**
2.  **Naive Approach**
3.  **Simple Average**
4.  **Simple Moving Average**
5.  **Simple Exponential Smoothing**
6.  **Holt's Linear Trend Model**
7.  **Holt-Winters' Model** (Additive and Multiplicative)
8.  **Autoregressive (AR) Model**
9.  **Moving Average (MA) Model**
10. **Autoregressive Moving Average (ARMA)**
11. **Autoregressive Integrated Moving Average (ARIMA)**
12. **Seasonal Autoregressive Integrated Moving Average (SARIMA)**

## Evaluation Metrics

The performance of each model is evaluated using the following metrics:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**

## Usage

1.  Clone the repository.
2.  Ensure you have the required libraries installed.
3.  Open `TSA_Graded_Exercise.ipynb` in Jupyter Notebook or Google Colab.
4.  Run the cells to execute the analysis and view the forecasts.

## Results

The notebook compares the RMSE and MAPE scores for all implemented models to identify the best forecasting method for this dataset.
