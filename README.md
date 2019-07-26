# Univariate-RecurrentNeuralNet
This was a graduate project where I explored recurrent neural networks with application to univariate time series data.

The data was drawn from Yahoo! Finance historical data for the Amazon stock. The Keras model that I used didn't seem to fully converge. It appeared that the results could be variable as the model kept trying to find better results even as I drew the learning rate down. I'm sure there's a solution to that issue but I just decided to find a statistical work-around. Namely I essentially turned it into an ensemble of neural networks. In some ways this makes sense. In others, it might be the silliest solution to a problem that I've ever had.

Though not included, I also utilized SAS to study the performance of an ARIMA model on the data.

Disclaimer: This project was not conducted for the sake of actually forecasting stock prices on the basis of closing price alone. This would be essentially impossible to profit on solely through daily results. The idea of this project was to successfully develop a model for time-series data using RNN's built in Keras.
