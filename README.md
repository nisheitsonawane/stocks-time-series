# stocks-time-series-using-python

The objective of this report is to conduct a comprehensive time series analysis of the stock prices of selected companies from the National Stock Exchange (Reliance, TCS, Infosys, Britannia, Nestle India, Vedanta Limited, Sunpharma, Dr Reddy, Bharti Airtel and HDFC Bank). The analysis aims to uncover insights, trends, and potential trading signals based on historical data, and utilize the Prophet forecasting model to predict future stock prices.

-----------------

## 1. Data Collection and Preprocessing
### Data Source
The historical stock price data is collected from the Yahoo Finance platform using the yFinance Python library. The data includes daily stock prices for the past five years, from May 11, 2018, to the current date, May 10, 2023.

### Data Preprocessing
The raw data is preprocessed to calculate the 100-day and 200-day Simple Moving Averages (SMA). These moving averages provide a smoothed representation of the stock prices and help identify trends and potential buy/sell signals.

## Time Zone Consideration
The analysis is conducted in the Indian Standard Time (IST) timezone since the stock prices are specific to companies listed on the National Stock Exchange of India.

## Exploratory Data Analysis
### Stock Data Analysis
Each stock's historical data is analyzed, including opening, high, low, and closing prices, as well as the calculated 100-day and 200-day SMAs. These analyses provide insights into the long term performance and trends of the stocks.

### Trading Signals
Based on the relationship between the closing price and the 100-day and 200-day SMAs, potential buy or sell signals are identified for each stock. These signals help investors make informed decisions about trading actions.

## Conclusion
### SMA explained
The choice of moving averages to use for analyzing historical data and making buy/sell decisions depends on various factors, such as the investment strategy, risk tolerance, and time horizon of the investor.
The 100 and 200-day simple moving averages are often used in long-term investment strategies. These moving averages can provide a broader perspective on the stock's long-term trends and potential support or resistance levels. Therefore, the choice of moving averages to use for your analysis depends on your investment strategy and time horizon. If you are a short-term trader, the 20 and 50-day moving averages may be more suitable for your analysis. However, if you are a long-term investor, you may consider using the 100 and 200-day moving averages.

### Meaning of the indication Buy/Sell
If closing price of current date stock is greater than its 100-day and 200-day simple moving average. We get an indication to Buy the stock.
It is a common technical analysis strategy to buy a stock when its current price is above its 100-day and 200-day simple moving average, which is often seen as a bullish signal indicating that the stock is trending upwards. Conversely, if the closing price of the current date stock is below its 100-day and 200-day simple moving average, it is often seen as a bearish signal indicating that the stock is trending downwards, and it may be a good time to sell the stock.

### Meaning of the forecast plot
In the Prophet plot, the light blue line represents the historical data and the dark blue line represents the forecasted values for the future period. The shaded blue area represents the uncertainty intervals for the forecast. Specifically, the light blue shaded area represents the uncertainty interval for the historical data, and the dark blue shaded area represents the uncertainty interval for the forecasted values.
