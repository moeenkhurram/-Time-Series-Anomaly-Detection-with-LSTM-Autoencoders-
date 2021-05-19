# Time Series Anomaly Detection with LSTM Autoencoders


The following steps will be followed to detect anomalies in Johnson & Johnson stock price data using an LSTM autoencoder:

Train an LSTM autoencoder on the Johnson & Johnson’s stock price data from 1980 to 2021. We assume that there were no anomalies and they were normal.

Using the LSTM autoencoder to reconstruct the error on the test data.

If the reconstruction error for the test data is above the threshold, we label the data point as an anomaly.
