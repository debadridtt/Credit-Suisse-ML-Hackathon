# Credit-Suisse-ML-Hackathon
Explanatory Stock Price Predictions

Stock markets have always been a fancy for companies, investors and traders. There is a plethora of investors investing or exiting the stocks at any point of time with different trading strategies and investment horizons. However the underlying objective of every type of investor is common "Maximize the returns and minimize the losses." To achieve this objective every investor is intrigued with one question “Is my stock price going to rise or fall in future".

People have been trying to find this answer from various angles. For some investors fundamentals are important and hence they rely on the fundamental strength of the stock. Others try to predict the movement of the stock based on technical analysis. Some try to predict the movement based on news about stocks and overall market sentiment while other tries to track the trend to predict the price of stock.

In this competition we challenge you to identify the predictability in the market based on technical analysis of stocks.

Problem Statement
The problem statement for this competition is to design a decision-making framework that can be used to predict actual return value of stock after 30th trading days.

To elaborate, we want to predict for list of given stocks and their return after 30th trading days.

In this competition we have given you 12 stocks of Banking and IT sector in csv format with last 5 years of stock details.

Above stock data has been downloaded from Yahoo Finance, but participants are free to download any other historical data from Yahoo finance if they are interested.
File format for stock data

table
Following technical indicators should be generated using any open source packages available in R or python for technical Analysis ( like TTR in R or Talib in Python)
Simple Moving Average ( 30, 40, 50 Days)
Exponential Moving Average ( 30, 40, 50 Days)
Aroon Oscillator ( 30, 40, 50 Days)
MACD signals
Relative Strength Index (RSI)
Bollinger Bands ( 30, 40, 50 Days)
Stochastic Oscillator
Stochastic momentum Indicator
Chande Momentum Oscillator
Commodity Channel Index ( 30, 40, 50 Days)
Chakin Volatility indicator ( 30, 40, 50 Days)
Trend Detection Index (30, 40, 50 Days)
Rate of Price Change (30, 40, 50 Days)
Rate of Volume Change (30, 40, 50 Days)
William % R (30, 40, 50 Days)
Participants are free to transform and derive more features from the above set of indicators from short term as well as long term perspective.
