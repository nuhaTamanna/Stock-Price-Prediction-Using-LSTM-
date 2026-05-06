# Stock-Price-Prediction-Using-LSTM-

LSTM Stock Price Prediction (with Live Market Data)

This project uses Long Short-Term Memory (LSTM) deep learning models to predict stock prices using historical data fetched in real-time from Yahoo Finance. It also includes a future trend forecaster that predicts whether the stock is likely to rise , fall , or remain stable.

Features

Live Market Data Fetching Fetch the latest stock data using the yfinance API: Supports any stock ticker (AAPL, TSLA, MSFT, etc.) Custom time periods (1y, 2y, 5y, max) Custom intervals (1d, 1h, 30m, 5m)

LSTM Deep Learning Model 60-day sequence training window Data normalization with MinMaxScaler Model saving and reloading support Predicts future stock values

Future Trend Detection Predicts N future days and classifies the trend as: Likely to Rise Likely to Fall Likely to Stay Stable

Visualizations Actual vs. Predicted price chart Highlight of highest predicted price Training vs. Testing data visualization

Category - Tools

Language - Python
Deep Learning - TensorFlow / Keras
Data Fetching - yfinance
Data Processing - pandas, numpy
Plotting - matplotlib
Scaling - scikit-learn (MinMaxScaler)

How to Run Requirements

Install all dependencies: pip install yfinance tensorflow pandas numpy matplotlib scikit-learn

RUN THE CODE Open the notebook in Google Colab. Enter a stock ticker symbol (e.g., AAPL, AMZN, MSFT). Enter a data period (e.g., 1y, 2y, 5y, max). Enter an interval (e.g., 1d, 1h, 30m, 5m).

The notebook will: Fetch data Train the LSTM Predict stock prices Predict the future trend Plot actual vs. predicted prices

Example Outputs Trend Output Future Trend: Likely to Rise

Graph Outputs Actual prices (black) Predicted prices (green) Highest predicted point highlighted

Data Source This project uses live market data fetched through the yfinance Python package:

https://pypi.org/project/yfinance/

Yahoo Finance is the underlying data provider accessed through this library.
