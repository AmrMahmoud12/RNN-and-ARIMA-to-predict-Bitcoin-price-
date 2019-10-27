# RNN-and-ARIMA-to-predict-Bitcoin-price
In this notebook I am comparing between neural network and ARIMA model in forecasting of bitcoin prices

First download your dataset from kaggle here :

https://www.kaggle.com/bigquery/bitcoin-blockchain

There are 4 csv files:

CSV files for select bitcoin exchanges for the time period of Jan 2012 to July 2018, with minute to minute updates of OHLC (Open, High, Low, Close), Volume in BTC and indicated currency, and weighted bitcoin price. Timestamps are in Unix time. Timestamps without any trades or activity have their data fields forward filled from the last valid time period.

If a timestamp is missing, or if there are jumps, this may be because the exchange (or its API) was down, the exchange (or its API) did not exist, or some other unforseen technical error in data reporting or gathering.
