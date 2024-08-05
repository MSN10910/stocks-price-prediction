# S&P 500 Prediction Model

This repository contains a machine learning model for predicting daily movements of the S&P 500 index using historical data from Yahoo Finance. The model is implemented using a Random Forest Classifier and is backtested on historical data to evaluate performance.

## Overview

The project aims to predict whether the S&P 500 index's closing price will increase or decrease the following day based on historical price and volume data. The model is trained using a Random Forest Classifier and evaluated using precision scores.

## Features

- **Data Collection**: Historical S&P 500 data is fetched using the Yahoo Finance API.
- **Feature Engineering**: Various features such as rolling averages and trends are computed.
- **Model Training**: A Random Forest Classifier is used for training and prediction.
- **Backtesting**: The model is backtested over multiple iterations to evaluate performance.
- **Probability-Based Predictions**: The model uses probability thresholds for making predictions.

## Dependencies

- `yfinance`: For fetching historical S&P 500 data.
- `pandas`: For data manipulation.
- `sklearn`: For machine learning and metrics.

You can install the required packages using `pip`:

```bash
pip install yfinance pandas scikit-learn
