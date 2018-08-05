# Stock-Price-Returns-Prediction 

A machine learning pipeline to predict stock price returns. 

## Overview

Market risk, strongly correlated with forecasting errors, needs to be minimized to ensure minimal risk in investment. This solution performs technical analysis on the stock price data and aims to predict the return price of stock after 30th trading days by minimizing the forecasting error by treating the forecasting problem as a regression problem, a popular suite of algorithms in machine learning. Ensemble learning, a powerful class of machine learning algorithms, which uses a collection of decision tress is used in this solution. 


Given past 5 years historical data, the aim is to predict stock price return after 30 trading days from a particular current day.


## Problem being solved

The learning model uses features from the stock price data with last 5 years of stock details from Yahoo Finance including open, High, Low, Volume, Close and Adjusted close. Further , some of the technical indicators viz; Simple Moving Average, Exponential Moving Average, Aroon Oscillator, MACD signals, Relative Strength Index (RSI), Bollinger Bands among others, have been derived from the stock price data with some of them calculated over a period of 30,40 & 50 days. 

The collective features are used for training the prediction model.


## Derived features
Following 12 technical indicators have been derived from the stock price data and have been collectively used for training. 

* Simple Moving Average
* Exponential Moving Average
* Aroon Oscillator
* MACD signals
* Relative Strength Index (RSI)
* Bollinger Bands
* Stochastic Oscillator
* Stochastic momentum Indicator
* Commodity Channel Index
* Chaikin Volatility indicator 
* Rate of Price Change 
* William % R 




## Dependencies

* Pandas
* LightBGM 
* numpy

The above libaries can be installed using [pip](https://pypi.org/project/pip/)   




