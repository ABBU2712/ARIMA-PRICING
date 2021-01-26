Here , in this project I have tried to implement two of the classical methods for the prediction of stock prices based on the previous data present with us . The methods used by me are :
1. ARIMA (Autoregressive Integrated Moving Averages)
2. LSTM(Long Short-Term Memory) Neural Networks 
For performing ARIMA these are the steps that must be followed :

i.  Visualize the Time Series Data
ii .Make the time series data stationary
iii.Plot the Correlation and AutoCorrelation Charts
iv. Construct the ARIMA Model
v. Use the model to make predictions
More info at: https://people.duke.edu/~rnau/arimrule.htm
WE have used the Seasonal Arima for final plotting and prediction.

For LSTM we have used the data as a staxked one to show the dependency of stock price of 4th day on it's preceeding 3 days . 
I have refered the given site for builiding it using tensorflow and keras .https://machinelearningmastery.com/time-series-prediction-with-deep-learning-in-python-with-keras/
The data set is taken from the kaggle website for New York Stock Exchange prediction.
https://www.kaggle.com/dgawlik/nyse
