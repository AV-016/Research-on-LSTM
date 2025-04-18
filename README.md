# Research-on-LSTM


Stock Price Prediction with LSTM
This project implements a Long Short-Term Memory (LSTM) model for stock price prediction. The model uses historical stock data (Open, Close, High, Low, and Volume) to predict future stock prices. The main focus of this project is to analyze and optimize the performance of the model by varying the number of epochs used for training.

Project Overview
The project uses the Yahoo Finance dataset for stock prices of multiple companies. It evaluates the performance of the LSTM model by testing different epoch sizes and optimizing the training process. The evaluation metrics used are RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error).

# The project aims to:

Predict stock prices using LSTM.

Compare model performance across different epoch sizes (20, 40, 60, 80, and fine-tuned epochs).

Visualize the results and evaluate the best performing configurations.

# Features
Stock price prediction using LSTM.

Model performance comparison for multiple epoch sizes.

RMSE and MAPE evaluation metrics.

Visualization of predicted vs. true stock prices.

Option to fine-tune epoch sizes for better performance.


# Dependencies

yfinance: For downloading stock price data from Yahoo Finance.

numpy: For numerical operations.

pandas: For data manipulation and analysis.

matplotlib: For data visualization.

scikit-learn: For data scaling and evaluation metrics.

tensorflow: For training and evaluating the LSTM model.



# Usage
Download Stock Data: The script automatically downloads stock data using the yfinance library for a given list of tickers.

Training and Prediction: The LSTM model is trained on the historical stock price data with different epoch sizes. It predicts future stock prices (1-day or 7-day ahead).

Visualization: The script generates plots comparing the true and predicted stock prices for each day.

Results: The RMSE and MAPE values are printed for each ticker and epoch configuration, and the results are displayed in a table.
