# autotrade
Stock/ETF auto-trading code in R for use with Interactive Brokers' IBAPI

Here is the auto-trading code that I presented at R Finance 2018 in Chicago on June 2. It works with many backtesting platforms 
because it accepts only 2 inputs: 
1) the new, recommended allocation that's generated by your signal, backtest, etc
2) the current allocation (i.e. your current portfolio) that is downloaded via IBAPI

You need 3 things to make Auto-trade work:
1) Interactive Broker's API installed
2) Python 3.6 installed
3) https://github.com/erdewit/ib_insync - Excellent Python module to interface with IBAPI very easily

I am actually a cardiac anesthesiologist; therefore, I have no formal computer science training. ANY CODE IMPROVEMENTS TO AUTOTRADE.R IS HIGHLY APPRECIATED.

DISCLAIMER: IF YOU USE ANY PART OF THIS AUTO-TRADING CODE, YOU FULLY ASSUME ALL THE FINANCIAL RISK ASSOCIATED WITH ITS USE.
FOR EDUCATIONAL USE ONLY. NOT FOR PRODUCTION USE.