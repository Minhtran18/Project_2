# INVESTMENT DASHBOARD

## Applying machine learning into the stock market

### Team Members: Syed Naqvi, Minh Tran, Rodrigo Guazzelli, Hsuan Liu, Abdullah Mamun

*The project is for study propose only*

***ADD PP LINK HERE***

### Summary

1.	Overview
2.	Introduction
3.	Data Sources
4.	Python Library
5.	Approach
6.	Dashboard Visualization
7.	Understanding the Theory
8.	Room for Improvement
9.	Q&A Session

---


### 1. Overview
The purpose of the dashboard is to present a detailed visualization of company insight with historical performance, technical indicators and predict the upcoming volatility applying machine learning. 
    
Target clients: Experienced investors.

### 2. Introduction

This project is an Interactive Stock Dashboard with Python with some Technical Indicators.

### 3. Data Source

Yahoo Finance

### 4. Python Library

Existing Libraries: Matplotlib, Pandas, Numpy, Plotly, Sklearn, Stats model.

New Libraries: Dash, Tkinter, Quantstats.

### 5. Approach

* Imported various libraries for visualization of stock performances.

* Imported Ticker and created a selection window for all the tickers available at Yfinance.

* Identified the trend and visualized the historical prices for the selected tickers (for coding refer Jupyter Notebook).

* Apply multiple models to predict future Price and volatility.

### 6. Dashboard Visualization

***ADD PICTURE HERE***

### 7. Understanding the Theory

Based on those models we prepared a dashboard consisting of 4 tabs:
    
### 7.1. Stock Overview

Composed by: 

Last closing price;

Industry;

Sector;

Business Summary.

You can select your desire period of Stock Performance:

1mo, 3mo, 6mo, 1y, 2y, 5y, 10y, ytd, max.

### 7.2. Return and Volatility matrix

### 7.2.1. Cumulative Return

A cumulative return is the aggregate daily return that the stock has gained or lost over time. The cumulative return is expressed as a percentage based on the stock closing price.

### 7.2.2. Sharpe Ratio

Sharpe ratio is a well-known and well-reputed measure of risk-adjusted return on an investment or portfolio. It can be used to evaluate the performance of an individual stock. 

The Sharpe ratio indicates how well an equity investment performs in comparison to the rate of the S&P 500 index and NASDAQ.

### 7.2.3. Rolling Standard Deviation

### 7.2.4. Rolling EWM


### 7.3. Algo Trading Strategy 

### 7.3.1. Algo Trading

It is usually applied for short term strategies because this is a high-risk strategy where the idea is to maximize gain and/or minimize losses.

Using Moving Average of Stock closing price as a Criteria, the graph shows points of BUY / SELL (Entry / Exit) recommendations when the 50-day moving average stock price goes below/under the 100-day moving average.
    
### 7.3.2.	Exponential Moving Average

The exponential moving average is also referred to as the exponentially weighted moving average. It reacts more significantly to recent price changes than a simple moving average (SMA), which applies an equal weight to all observations in the period.
    
### 7.3.3.	Bollinger Banda

It is a technical analysis tool for generating oversold or overbought signals composed with three lines: A simple moving average low, middle and upper band.
    
It can tell you how closer the price moves to the upper band (more overbought the market), and the closer the price moves to the lower band (the more oversold the market)

### 7.3.4.	Random Forest Model

A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.

### 7.4.	Predictions with Machine Learning Techniques

### 7.4.1.	LSTM RNN Predicted vs Actual Stock Price with Bollinger 

### 7.4.2.	Predicted vs Actual Return

### 7.4.3.	ARMA Forecast

The Auto Regressive Moving Average (ARMA) model consists of two parts, an autoregressive (AR) part and a moving average (MA) part. The Auto Regressive part involves regressing the variable on its own lagging(past) values.

### 7.4.4.	ARIMA Forecast

The Auto Regressive Integrated Moving Average (ARIMA) model is a famous and widely used forecasting method for time-series prediction. ARIMA models can capture a suite of different standard temporal structures in time-series data. The model is a measure of how many non-seasonal differences are needed to achieve stationarity.

If no differencing is involved in the model, then it becomes simply an ARMA.
    
### 7.4.5.	Volatility Forecast.
    
### 8. Room for Improvement:

* Adding more parameters to build better prediction model.

* Adding more modelling options.

* Improve the Dashboard running speed.

### 9. Q&A Session 
