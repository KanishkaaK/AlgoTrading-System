# Algo-Trading System with ML & Automation

This project fetches stock market data using yFinance, applies RSI + Moving Average strategy, logs trades to Google Sheets, and uses ML (Decision Tree, Logistic Regression) to predict next-day price movement.

## Features:
-  RSI + 20DMA/50DMA crossover strategy
-  Google Sheets automation via `gspread`
-  ML Model for stock movement prediction
-  Accuracy: ~20% using logistic regression

## How to Run
1. Clone the repo
2. Open `algo_trading_strategy.ipynb` in Google Colab
3. Upload credentials.json if using Sheets logging
4. Run cells step by step

## Requirements
- yfinance
- pandas
- sklearn
- gspread
- oauth2client
