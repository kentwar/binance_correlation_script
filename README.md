## binance_correlation_script

A jupyter notebook that calculates correlation matrices for crypto coins in binance exchange

This script will require a binance API key to run and will do the following

1. Download binance coin data
2. Produce correlation matrix for
  #a - Raw Coin value (1 minute intervals)
  #b - Detrended coin value (first difference)
  #c - Detrended coin value (rolling mean)
  #d - rolling mean 

Used Python 3.7
