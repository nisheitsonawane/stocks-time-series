# stocks-time-series-using-python

The objective of this report is to conduct a comprehensive time series analysis of the stock prices of selected companies from the National Stock Exchange (Reliance, TCS, Infosys, Britannia, Nestle India, Vedanta Limited, Sunpharma, Dr Reddy, Bharti Airtel and HDFC Bank). The analysis aims to uncover insights, trends, and potential trading signals based on historical data, and utilize the Prophet forecasting model to predict future stock prices.

-----------------

# 1. Data Collection and Preprocessing
### Data Source
The historical stock price data is collected from the Yahoo Finance platform using the yFinance Python library. The data includes daily stock prices for the past five years, from May 11, 2018, to the current date, May 10, 2023.

## Data Preprocessing
The raw data is preprocessed to calculate the 100-day and 200-day Simple Moving Averages (SMA). These moving averages provide a smoothed representation of the stock prices and help identify trends and potential buy/sell signals.

# Time Zone Consideration
The analysis is conducted in the Indian Standard Time (IST) timezone since the stock prices are specific to companies listed on the National Stock Exchange of India.

