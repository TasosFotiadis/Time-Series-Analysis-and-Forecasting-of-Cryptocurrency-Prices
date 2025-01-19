# Cryptocurrency Price Forecasting using Time Series Analysis

## Overview
This project focuses on analyzing and forecasting Cardano (ADA) cryptocurrency prices using time series analysis techniques. The goal is to predict future prices by leveraging statistical models and machine learning techniques, comparing their effectiveness for accurate financial forecasting.

## Objectives
- Clean and preprocess the raw cryptocurrency data.
- Explore trends, seasonality, and patterns in the time series data.
- Build and evaluate ARIMA, SARIMA, and LSTM models for price forecasting.
- Compare models using evaluation metrics like MAE, MSE, and MAPE.
- Provide actionable insights and recommendations.

## Features
1. **Data Preprocessing**: 
   - Handled missing values and ensured stationarity for time series modeling.
2. **Exploratory Analysis**: 
   - Visualized trends, seasonality, and volatility in cryptocurrency prices.
3. **Model Building**: 
   - ARIMA and SARIMA models for statistical analysis.
   - LSTM model for capturing complex, non-linear patterns.
4. **Model Evaluation**:
   - Compared models based on AIC, BIC, and forecasting accuracy metrics.
5. **Forecasting**:
   - Generated future price predictions with confidence intervals.

## Results
- ARIMA(2,1,2) was the best-performing model based on AIC/BIC and accuracy metrics.
- LSTM provided competitive results but required more data and tuning.
- Forecasts demonstrated practical value for short-term investment decisions.

## Tools and Technologies
- **Languages**: Python, R
- **Libraries**: 
  - Python: TensorFlow, sklearn, matplotlib, pandas
  - R: fable, tsibble, ggplot2
- **Techniques**: Time Series Analysis, ARIMA, SARIMA, LSTM

## Files Included
1. `Cardano_Project.ipynb`: Notebook .ipynb with R containing the project.
2. `LSTM_interpretation_Cardano_Project.ipynb`: Alternative implemantation of ARIMA using LSTM method in Python.
3. `coin_Cardano.csv`: Dataset containing Cardano price data.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/TasosFotiadis/crypto-forecasting.git
   cd crypto-forecasting
