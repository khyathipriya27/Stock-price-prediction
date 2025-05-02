# Stock-price-prediction
# 📈 Stock Price Movement Prediction

Predict whether a stock's price will go up or down the next day using historical price data and machine learning.

## 🔍 Problem Statement
Use technical indicators from stock price data to predict short-term movement (UP or DOWN) using a binary classification model.

## 📊 Features Used
- Returns (daily)
- Moving Averages (MA5, MA10, MA20)
- RSI (Relative Strength Index)
- EMA10, EMA20
- MACD, Signal Line
- Bollinger Bands (Upper, Lower)
- Momentum (10-day)
- Volatility (10-day std)

## 🧠 Model Used
- Random Forest Classifier (sklearn)

## 🎯 Evaluation
- Accuracy, Precision, Recall
- Strategy backtest vs. market
- Final prediction for next-day movement

## 📈 Results
- Strategy outperformed the market in early test periods
- Final model accuracy: `XX%` (fill with your result)
- Predicted: 📈 (or 📉) for the next day

## ✅ Next Steps
- Tune model hyperparameters
- Add more technical/fundamental indicators
- Deploy with a scheduled update pipeline (daily)

## 📁 How to Run
1. Install dependencies (`pip install yfinance pandas sklearn matplotlib seaborn`)
2. Open the notebook
3. Run all cells

