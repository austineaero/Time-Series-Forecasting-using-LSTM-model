# Time Series Forecasting using LSTM model
This LSTM model in python uses Tensorflow and Keras to predict values of a time series X number of steps into the future using a window of Y values from the past.

This code is able to:
- read in the csv file and normalize the data
- split data into train/test
- create the sequences based on the X and Y values detailed above
- take in new non-normalized data, normalize it to run against the model, and then reverse the normalization of the returned prediction to be able to view it in the original raw     scale.
