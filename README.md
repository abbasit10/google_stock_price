# Stock Market Data Scraping and Analysis in Python
This project aims to provide a comprehensive guide to scraping stock market data using the yfinance library and performing various analyses to gain insights into the data. This repository contains a Jupyter notebook that demonstrates how to scrape, analyze, and visualize stock market data using Python. The notebook includes data fetching, preprocessing, exploratory data analysis, and time series forecasting.

## Key Notebook sections
### Stationarity Check: 
The data was checked for stationarity and found to be non-stationary.

### Data Decomposition: 
The data was decomposed to observe the trend, seasonality, and noise components.

### Differencing: 
Plotted the original series, first differencing, and second differencing to determine the value of d, which was found to be 1.

### Determine p and q: 
Used ACF and PACF plots to determine the values of p and q.

* Value of p was determined to be 3
* Value of q was determined to be 2

### ARIMA Model: 
Attempted to apply ARIMA, but found it unsuitable for seasonal data.

### SARIMA Model: 
Applied SARIMA to better predict the seasonal data and obtained the prediction results.


