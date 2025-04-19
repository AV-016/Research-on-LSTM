# Stock Price Prediction Using LSTM

This repository contains a machine learning project focused on predicting stock prices using Long Short-Term Memory (LSTM) networks. The research explores the performance of LSTM models on stock data for various companies and compares the effectiveness of hyperparameter tuning. The project also evaluates the model's performance using metrics such as RMSE and MAPE over different prediction horizons (1-day, 7-day predictions).

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Data](#data)
5. [Model](#model)
6. [Evaluation](#evaluation)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)

## Overview

The objective of this project is to predict future stock prices using an LSTM-based model. The model is trained on historical stock data, with a focus on predicting prices for the following companies:
- **Apple (AAPL)**
- **Microsoft (MSFT)**
- **Google (GOOGL)**
- **Amazon (AMZN)**

The project includes:
- **Data preprocessing**: Feature engineering and scaling of stock data.
- **LSTM Model**: Time series forecasting using LSTM networks.
- **Hyperparameter tuning**: Tuning LSTM hyperparameters like epochs and units.
- **Evaluation**: Using RMSE and MAPE metrics for evaluating model performance.

## Features

- **Stock Data Analysis**: Data collection and cleaning for AAPL, MSFT, GOOGL, and AMZN stock prices.
- **Model Training**: LSTM network implementation for time series forecasting.
- **Hyperparameter Tuning**: A grid search-based approach for hyperparameter optimization.
- **Prediction Horizons**: Predictions made for 1-day ahead, 3-days ahead, and 7-days ahead.
- **Evaluation Metrics**: RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error) used for evaluating model accuracy.

## Requirements

Before running this project, ensure you have the following Python packages installed:

TensorFlow: For building and training the LSTM model.

Keras: A high-level neural network API running on top of TensorFlow.

pandas: For data manipulation and analysis.

numpy: For numerical operations.

matplotlib: For plotting graphs and visualizations.

scikit-learn: For model evaluation metrics and preprocessing.


Stock price data for AAPL, MSFT, GOOGL, and AMZN is fetched using the Yahoo Finance API. 
The data contains:
Open, High, Low, Close, and Volume information for each stock.
Data is preprocessed and scaled for use in the LSTM model.



# Hyperparameters:
LSTM Units: Number of units in the LSTM layer.

Dense Units: Number of units in the dense layer.

Epochs: Number of training epochs.

Batch Size: Number of samples per gradient update.

The model is trained for different values of these hyperparameters to evaluate their performance.


## Evaluation
After training, the model's performance is evaluated using two metrics:

RMSE (Root Mean Squared Error): Measures the average magnitude of the errors.

MAPE (Mean Absolute Percentage Error): Measures the accuracy as a percentage.

Performance is evaluated for 1-day, 3-day, and 7-day predictions.

