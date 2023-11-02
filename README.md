# Time-Series-Forecasting
Weekly Sales Forecast

# Walmart Weekly Sales Forecast

## Project Overview
This project aims to forecast Walmart's weekly sales using historical data provided by the company. The dataset includes sales data from 45 stores, with additional information such as store size, type, and regional factors. Special attention is given to holiday periods, which are flagged in the dataset to ascertain their impact on sales.

## Abstract
Our analysis utilizes multiple approaches to forecast weekly sales. Initially, we suggested a SARIMA model based on time series data analysis. Subsequently, we employed a tree-based Machine Learning algorithm, the Random Forest regressor, which provided the least absolute error, indicating superior forecasting ability compared to SARIMA models.

## Introduction
Understanding consumer demand in advance is crucial for retail giants like Walmart. Our project provides data-driven approaches to predict sales, focusing on different departments and store locations. The goal is to enable Walmart to maintain an optimal inventory level, thereby enhancing profitability.

## Dataset
The dataset comprises weekly sales data from 45 Walmart stores, including information on holidays, store attributes, and external factors like temperature and fuel prices.

## Methodology
Our methodology involved a comparative analysis of different forecasting models:

1. **SARIMA Model**: We started with a Seasonal Autoregressive Integrated Moving Average (SARIMA) model, which is well-suited for time series data with seasonality. The model parameters were selected based on the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots.

2. **Random Forest Regressor**: We then shifted to a more advanced model, the Random Forest regressor. This ensemble learning method combines multiple decision trees to improve predictive accuracy and control over-fitting. The Random Forest model was fine-tuned through hyperparameter optimization, including the number of trees (estimators) and the depth of each tree.

3. **Feature Selection**: To enhance the model's performance, we conducted feature selection based on the feature importance scores generated by the Random Forest. We tested various combinations of features, removing those with low importance and collinearity to prevent model complexity and overfitting.

4. **Model Evaluation Metrics**: The models were evaluated using Weighted Mean Absolute Error (WMAE), which gives higher weight to errors during holiday weeks, and R-squared scores to measure the proportion of variance explained by the model.

The best-performing model was selected based on the lowest WMAE score and the highest R-squared value, indicating both accuracy and reliability in the predictions.

## Model Evaluation
The Random Forest regressor, an ensemble method, was chosen for its robustness and ability to avoid overfitting. Our model includes 200 estimators and considers a range of features after preprocessing.

## Results
The best model achieved the lowest WMAE, indicating high accuracy in forecasting weekly sales. Feature importance and selection played a significant role in model optimization.
