## About these scripts

These scripts were created in order to support the selection of coin trading lists for use with automated trading strategies. Specifically, this one https://github.com/edeng23/binance-trade-bot

## How to use

Install requirements with 

```python
python install -r requirements.txt
```

The scripts are python notebooks, whilst they use python 3, you will need jupyter notebook (or something that reads notebook docs) to access it.
https://jupyter.org/


## Automatic Correlated Coin List - auto_coin_list.ipynb
##### WARNING - This can take some time to run as it downloads a lot of data from binance servers
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


