# Quantitative Portfolio Management Assignment 

## Description
This project analyzes daily stock returns for FAANG stocks (Meta, Amazon, Apple, Netflix, and Alphabet) and companies in the S&P 500 index over different time periods. The analysis is divided into two main sections:

1. **FAANG Stock Analysis**:
   - **Q1.1**: Download daily stock prices for FAANG stocks (META, AMZN, AAPL, NFLX, GOOG) from January 2015 to December 2020.
   - **Q1.2**: Compute the mean, variance, and covariance of daily returns for each stock.
   - **Q1.3**: Calculate the skewness and excess kurtosis of each stock's returns and assess if they follow a Normal distribution.

2. **S&P 500 Stock Analysis**:
   - **Q2.1**: Download the list of S&P 500 companies and their ticker symbols, and build a DataFrame of daily stock prices from January 2000 to December 2022. Drop columns with only NaN values and companies with excessive missing data.
   - **Q2.2**: Calculate log returns for the S&P 500 stocks.
   - **Q2.3**: Compute the annualized mean return, volatility, and Sharpe ratio for each stock.
   - **Q2.4**: Evaluate whether it makes sense to choose portfolio weights based solely on Sharpe ratios.

The code is designed to facilitate reproducible analysis and includes necessary data cleaning and financial metric calculations for understanding stock performance.


## Requirements
- numpy
- pandas
- matplotlib
