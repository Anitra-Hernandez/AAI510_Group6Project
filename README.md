# 📈 Stock Price Prediction Project

This project explores forecasting stock closing prices using three different models:
- Linear Regression (walk-forward forecasting)
- LSTM (Long Short-Term Memory neural network)
- ARIMA (AutoRegressive Integrated Moving Average)

Our goal is to evaluate which model performs best on historical stock data, and understand their strengths and limitations.

## 🚀 Features

- Predicts future stock closing prices
- Walk-forward forecast using lag features
- LSTM for deep sequence modeling
- ARIMA for classical time-series analysis
- RMSE and R² metrics for model comparison
- Clean visualizations of predictions vs. actual prices

## 📊 Results Summary

| Model            | RMSE   | R²     |
|------------------|--------|--------|
| **ARIMA**        | 20.60  | 0.9920 |
| **Linear Reg.**  | 49.17  | 0.9606 |
| **LSTM**         | 101.25 | 0.8032 |

## 🛠 Requirements

- Python 3.10+
- pandas
- numpy
- scikit-learn
- matplotlib
- statsmodels
- torch (for LSTM)

## 📝 Notes
- We focused on a single stock ticker (e.g. NFLX) for consistency

- Only past OHLC data was used — no external features like news or sentiment

- LSTM performance was lower due to limited data and minimal tuning

## 📦 Future Work
- Add multi-stock support

- Use macroeconomic and news data

- Integrate into a web interface for real-time forecasting

## 👥 Contributors

**Mohammad** – Linear Regression model

**Pallav** – LSTM model implementation and tuning

**Anitra** – ARIMA modeling