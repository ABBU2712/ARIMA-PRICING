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

## Results

The given model tries to draw a comparison between two of the models. We tried to compare the results obtained in both of the methods implemented. LSTM's implementation is more complex, as compared to that of ARIMA. The key differences observed are:

1. For a relatively simple stock price dataset with clear trends, seasonality, and stationary properties, and a more interpretable model, ARIMA might be a suitable choice.

2. If the stock price data is complex, exhibits non-linear behavior, or we want to capture long-term dependencies and intricate patterns, LSTM or other deep learning approaches may be more effective.

3. For a smaller dataset ARIMA seems to outperform LSTM significantly with a smaller Standard deviation. As we increase the size of the dataset, we see a significant change in the performance of LSTM. The low volatility of the ARIMA 
  shows that it is impractical to be used for the practical purposes
