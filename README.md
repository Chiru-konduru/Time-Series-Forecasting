# Time-Series-Forecasting
Weekly Sales Forecast

Project Overview
This project aims to forecast Walmart's weekly sales using historical data provided by the company. The dataset includes sales data from 45 stores, with additional information such as store size, type, and regional factors. Special attention is given to holiday periods, which are flagged in the dataset to ascertain their impact on sales.

Abstract
Our analysis utilizes multiple approaches to forecast weekly sales. Initially, we suggested a SARIMA model based on time series data analysis. Subsequently, we employed a tree-based Machine Learning algorithm, the Random Forest regressor, which provided the least absolute error, indicating superior forecasting ability compared to SARIMA models.

Introduction
Understanding consumer demand in advance is crucial for retail giants like Walmart. Our project provides data-driven approaches to predict sales, focusing on different departments and store locations. The goal is to enable Walmart to maintain an optimal inventory level, thereby enhancing profitability.

Dataset
The dataset comprises weekly sales data from 45 Walmart stores, including information on holidays, store attributes, and external factors like temperature and fuel prices.

Methodology
We experimented with various models to identify the best-performing Random Forest model through feature selection. The performance was evaluated using Weighted Mean Absolute Error (WMAE) and R-squared scores.

Model Evaluation
The Random Forest regressor, an ensemble method, was chosen for its robustness and ability to avoid overfitting. Our model includes 200 estimators and considers a range of features after preprocessing.

Results
The best model achieved the lowest WMAE, indicating high accuracy in forecasting weekly sales. Feature importance and selection played a significant role in model optimization.
