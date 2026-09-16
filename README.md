# Crypto Price Analysis & Forecasting

## Overview

This project analyzes Bitcoin (BTC) and Ethereum (ETH) price data from 2023–2025.

The project was completed as part of the **Business Analytics & AI** course at **Tokyo International University**.

The analysis focuses on cryptocurrency price trends, volatility, correlation, and price forecasting.

## Objectives

- Analyze BTC and ETH price movements
- Compare cryptocurrency volatility
- Examine the relationship between BTC and ETH
- Build models for cryptocurrency price forecasting
- Evaluate model performance using MAE, RMSE, and MAPE

## Data Analysis

The project includes:

- Descriptive statistics
- Daily returns
- 20-day and 50-day moving averages
- 30-day rolling volatility
- BTC–ETH return correlation
- Rolling correlation
- Extreme price movement analysis

## Forecasting Models

Three forecasting approaches were examined:

1. Naive forecasting
2. ARIMA
3. Linear Regression using lag and technical features

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

## Key Findings

The analysis found that:

- BTC and ETH showed an overall upward movement during the analyzed period.
- ETH showed higher volatility than BTC.
- BTC and ETH had a strong positive correlation.
- The Linear Regression model produced lower forecasting errors than the other models in the project evaluation.

## Features Used

The forecasting analysis used:

- Previous-day closing price
- 3-day lag
- 7-day lag
- 20-day moving average
- 50-day moving average
- 30-day rolling volatility

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ARIMA
- Jupyter Notebook / Google Colab

## Project Structure

```text
crypto-price-analysis/
├── README.md
├── crypto-price-analysis.ipynb
├── data/
├── plots/
└── presentation/
