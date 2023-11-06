# Stock Price Prediction Project

In this project, we aim to predict stock prices using two classical methods: **ARIMA** (Autoregressive Integrated Moving Averages) and **LSTM** (Long Short-Term Memory) Neural Networks.

## Table of Contents

- [Stock Price Prediction Project](#stock-price-prediction-project)
  - [Description](#description)
  - [Methods Used](#methods-used)
    - [ARIMA (Autoregressive Integrated Moving Averages)](#arima-autoregressive-integrated-moving-averages)
      - [Steps for ARIMA](#steps-for-arima)
    - [LSTM (Long Short-Term Memory) Neural Networks](#lstm-long-short-term-memory-neural-networks)
  - [Data Sources](#data-sources)

## Description

This project focuses on predicting stock prices based on historical data. We employ two different methods, **ARIMA** and **LSTM**, to create predictive models. By using these methods, we aim to provide insights into stock price movements and forecast future prices.

## Methods Used

### ARIMA (Autoregressive Integrated Moving Averages)

**ARIMA** is a time series forecasting method that involves the following steps:

1. Visualize the Time Series Data.
2. Make the time series data stationary.
3. Plot the Correlation and AutoCorrelation Charts.
4. Construct the ARIMA Model.
5. Use the model to make predictions.

For more information on **ARIMA**, refer to: [ARIMA Rules](https://people.duke.edu/~rnau/arimrule.htm).

We have used Seasonal **ARIMA** for the final plotting and prediction.

### LSTM (Long Short-Term Memory) Neural Networks

**LSTM** is a deep learning technique used for time series prediction. In this project, we have implemented **LSTM** to capture dependencies in stock prices over multiple days.

For guidance on implementing **LSTM** with TensorFlow and Keras, we referred to this resource: [Time Series Prediction with Deep Learning in Python with Keras](https://machinelearningmastery.com/time-series-prediction-with-deep-learning-in-python-with-keras/).

## Data Sources

The dataset used in this project is obtained from the Kaggle website, specifically the New York Stock Exchange dataset. You can find the dataset here: [NYSE Stock Data on Kaggle](https://www.kaggle.com/dgawlik/nyse).

Feel free to customize this README to include more details or links related to your project. This revised README provides a clear and organized overview of your stock price prediction project.
