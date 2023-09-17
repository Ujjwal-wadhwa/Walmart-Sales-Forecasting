# Walmart Sales Time Series Forecasting

![Walmart Logo](walmart_logo.png) 

This project focuses on the time series forecasting of Walmart sales data using machine learning and deep learning techniques. It aims to predict weekly sales for various departments across different Walmart stores, taking into account historical sales data and holiday markdown events.

## Dataset Description

### Retail Data Challenge

One of the key challenges in modelling retail data is making decisions based on limited historical data. This project addresses this challenge by providing historical sales data for 45 Walmart stores located in different regions, each containing multiple departments. The dataset also includes selected holiday markdown events known to impact sales, though predicting their specific impact on departments remains challenging.

## Datasets

The project utilizes the following datasets:

- **train.csv** - Contains historical sales data with attributes such as Store, Dept, Date, Weekly_Sales, and IsHoliday.

- **stores.csv** - Provides additional information about stores, including Store Type and Size.

- **features.csv** - Includes features like Temperature, Fuel_Price, and various Markdowns.

## Machine Learning Models

We've implemented several machine learning models for sales forecasting, including:

- Linear Regression
- Random Forest Regression
- K Neighbors Regression
- XGBoost Regression
- Custom Deep Learning Neural Network

## Model Comparison

We compared the models based on their accuracy. The best-performing model was:

- **Random Forest Regression Model**
  - Accuracy: 97.84%

This model achieved the highest accuracy among the tested models.

## Data Preprocessing

We performed various data preprocessing steps, including handling missing values, merging datasets, splitting the date column, aggregating weekly sales, outlier detection, and one-hot encoding of categorical columns.

## Citations

- [Walmart Recruiting - Store Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting) - The dataset used in this project was obtained from Kaggle.
