## auto_coin_list.ipynb

An automatic coin list generator that will scout binance for the most correlated trading pairs to a single starting coin. It will 

1. Provide an automatic list for running a reverse greedy trading algorithm
2. Plot a volatility histogram
3. Plot correlation heat maps over different periods
4. calculate trade volume in USD and warn against coins at high risk of slippage



## binance_correlation_script

A jupyter notebook that calculates correlation matrices for crypto coins in binance exchange

This script will require a binance API key to run and will do the following


**1.** Download binance coin data from coinlist

**2.** Produce correlation matrix for

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Raw Coin value** (1 minute intervals)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (first difference)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Detrended coin value** (rolling mean) 
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**rolling mean** itself

coded in Python 3.7


