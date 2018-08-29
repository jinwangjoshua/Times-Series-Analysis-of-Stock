# Times-Series-Analysis-of-Amazon-Stock

### 1.1 Goal
In this repo, I tried to explore if we can predict the stock of Amazon(AMZN) with 15 years' historical data. The whole idea is based on time series models, say ARIMA(AutoRegressive Integrated Moving Average). R and R-studio are involved here.

### 1.2 Dataset
In this paper, we imported and read the past stock data for Amazon from Yahoo Finance(??????!!) and plotted it in order to understand the nature of data. The Dataset consist of daily stock prices from January 2000 to September 2017. To analyse the time series, this paper includes two time series objects "ts" and "xts" for different time series analysis.

### 1.3 Data pre-processing
Data wrangling is done in order to fill out missing stock prices when stock market is closed and then we extracted relevant data to perform further time series analysis. We also decompose the time series to get the trend, seasonal, and random component and make visualized it.

For the decomposition, we includes Simple Moving Average, it is calculated for a different number of time periods by adding the closing price for a number of time periods and then dividing this total by the number of time periods, which gives the average price of the security over the time period. It smooth out the volatility. It helps to understand trend in data.

### 1.4 Time series models (technical merit)
On training dataset, different time series methods, Holt-Winter Exponential Smoothing and Autoregressive Integrated Moving Average are applied to fit and predict the stock prices.

### 1.5 Evaluation method
Finally Root Mean Square Error(RMSE) is calculated for above methods and concluded with best possible method for stock prediction. 

### Wang Jin

