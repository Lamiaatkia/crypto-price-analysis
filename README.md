# Crypto Price Analysis & Forecasting

## 📌 Overview

This project analyzes Bitcoin (BTC) and Ethereum (ETH) price data and compares three different forecasting approaches.

The project was developed as part of the **Business Analytics & AI** course at Tokyo International University.

## 🎯 Objective

The objective was to analyze cryptocurrency price trends, volatility, and correlation, and evaluate forecasting models that could support the design of a two-tier Conservative/Growth investment product.

## 📊 Data Analysis

The analysis focused on:

- Bitcoin (BTC)
- Ethereum (ETH)
- Price trends
- Daily returns
- Volatility
- Correlation
- Moving averages

The project used 2023–2025 data for the analysis.

## 🤖 Forecasting Models

Three models were compared:

### 1. Naive Baseline

The next day's price is predicted using the current day's closing price.

### 2. ARIMA(1,1,1)

A time-series forecasting model using historical price information.

### 3. Linear Regression

A regression model using engineered features:

- Lag 1
- Lag 3
- Lag 7
- 20-day moving average
- 50-day moving average
- 30-day rolling volatility

## 📈 Model Evaluation

The models were evaluated on a 90-day test set using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

### BTC MAPE

| Model | MAPE |
|---|---:|
| Naive Baseline | 3.43% |
| ARIMA(1,1,1) | 2.63% |
| Linear Regression | 2.56% |

### ETH MAPE

| Model | MAPE |
|---|---:|
| Naive Baseline | 9.66% |
| ARIMA(1,1,1) | 7.75% |
| Linear Regression | 7.43% |

## 🔍 Key Findings

The Linear Regression model produced the lowest reported MAE, RMSE, and MAPE among the three tested approaches for both BTC and ETH on the stated 90-day test set.

The project also found:

- BTC increased substantially over the analyzed period.
- ETH showed higher average volatility than BTC.
- BTC and ETH showed a positive correlation.
- Extreme price movements presented challenges for forecasting models.

## ⚠️ Limitations

- The data used in the project was simulated to match the statistics used in the analysis.
- Production implementation would require live market data.
- Cryptocurrency markets can experience sudden changes that are difficult for historical models to capture.
- The models did not include news or social-media sentiment.

## 🔮 Future Improvements

Potential improvements include:

- Live cryptocurrency API data
- On-chain metrics
- Google Trends and sentiment data
- RSI
- MACD
- Bollinger Bands
- LSTM models
- XGBoost
- Cross-asset features
- Value at Risk (VaR)

## 🛠️ Tools & Concepts

- Python
- Data Analysis
- Exploratory Data Analysis (EDA)
- Time Series Forecasting
- ARIMA
- Linear Regression
- Feature Engineering
- Model Evaluation
- MAE
- RMSE
- MAPE

## 🎓 Academic Project

**Course:** Business Analytics & AI  
**University:** Tokyo International University  
**Year:** 2026
