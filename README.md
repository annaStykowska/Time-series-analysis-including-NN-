# Time-series-analysis-insluding-NN-
In this file there is some of my analysis of electricity time series for three different countries, which I was performing during writing my master thesis. <br>
There are two notebooks: ARIMA_sezonowosc.ipynb and NN_LSTM, GRU.ipynb.
## ARIMA_sezonowosc.ipynb
* elements of data exploration
* preparation of time series for further analysis (decomposition of TS, stationarity)
* prediction of time series using ARIMA (an autoregressive integrated moving average) and automatic seasonal ARIMA 
## NN_LSTM, GRU.ipynb
Prediction of time series using neural networks - LSTM and GRU cells. <br>
The most important and longest part is the appropriate selection of parameters. <br>
To significantly shorten the program's running time you can change variable n_trials (default: n_trials = 30) in "Trening" section - in this part is setted optimal number of model layers and neurons by optimizer.
But be careful, the results can be worse if optimizer doesn't have enough number of trials.
## Insights
You can read my insights in polish in TimeSeriesForecast.pdf. <br>
There are comparisons of various methods for time series of power grid loads in chosen countries. 
