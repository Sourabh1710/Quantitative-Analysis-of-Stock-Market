# Quantitative Analysis of Stock Market

## Introduction
Quantitative Analysis in the stock market is a financial methodology that utilizes mathematical and statistical techniques to analyze stocks and financial markets. In this project, I perform a Quantitative Analysis of the stock market using Python.

## Process I Followed
To analyze stock market data, I followed a systematic process:
1. Clearly defined the objectives and questions to be answered.
2. Identified the key performance indicators (KPIs) relevant to the analysis.
3. Gathered historical stock market data, including prices, volumes, and other relevant financial indicators.
4. Cleaned and preprocessed the data to handle missing values, outliers, and errors.
5. Conducted initial analysis to understand data distributions, patterns, and correlations.
6. Implemented various strategies based on quantitative analysis.

## Dataset
The [dataset](https://statso.io/quantitative-analysis-case-study/) contains the following columns for stock market data:
- **Ticker:** The stock ticker symbol.
- **Date:** The trading date.
- **Open:** The opening price of the stock for the day.
- **High:** The highest price of the stock during the day.
- **Low:** The lowest price of the stock during the day.
- **Close:** The closing price of the stock for the day.
- **Adj Close:** The adjusted closing price, which accounts for all corporate actions such as dividends, stock splits, etc.
- **Volume:** The number of shares traded during the day.

## Analyses Performed

### 1. Descriptive Statistics
I calculated summary statistics such as mean, median, standard deviation, and more for the closing prices of each stock.
```
        count        mean        std         min         25%         50%  \
Ticker                                                                     
AAPL     62.0  158.240645   7.360485  145.309998  152.077499  158.055000   
GOOG     62.0  100.631532   6.279464   89.349998   94.702501  102.759998   
MSFT     62.0  275.039839  17.676231  246.270004  258.742500  275.810013   
NFLX     62.0  327.614677  18.554419  292.760010  315.672493  325.600006   

               75%         max  
Ticker                          
AAPL    165.162506  173.570007  
GOOG    105.962503  109.459999  
MSFT    287.217506  310.649994  
NFLX    338.899994  366.829987  
```

### 2. Time Series Analysis
I examined trends and patterns over time, focusing on the closing prices of stocks.

![Time Series Analysis](https://github.com/Sourabh1710/Quantitative-Analysis-of-Stock-Market/blob/main/images/Time%20Series%20of%20Closing%20Prices.png)

### 3. Volatility Analysis
I calculated and compared the volatility (standard deviation) of the closing prices for each stock.

![Volatility Analysis](https://github.com/Sourabh1710/Quantitative-Analysis-of-Stock-Market/blob/main/images/Volatility%20of%20Closing%20Prices%20(Standard%20Deviation).png)

### 4. Correlation Analysis
I performed a correlation analysis to understand how stock prices of different companies are related.

![Correlation Analysis](https://github.com/Sourabh1710/Quantitative-Analysis-of-Stock-Market/blob/main/images/Correlation%20Matrix%20of%20Closing%20Prices.png)

### 5. Comparative Analysis
I compared the performance of different stocks based on their returns over the period.

![Comparative Analysis](https://github.com/Sourabh1710/Quantitative-Analysis-of-Stock-Market/blob/main/images/Percentage%20Change%20in%20Closing%20Prices.png)

### 6. Risk-Return Trade-off Analysis
I analyzed the balance between the potential risks and rewards of different stocks.

![Risk Vs. Return](https://github.com/Sourabh1710/Quantitative-Analysis-of-Stock-Market/blob/main/images/Risk%20vs.%20Return%20Analysis.png)

## Summary
This project demonstrates how I performed Quantitative Analysis of the Stock Market using Python. I explored various statistical concepts, including descriptive statistics, time series analysis, correlation analysis, volatility analysis, comparative analysis, and risk-return trade-off analysis.

## Author
Sourabh Sonker <br>
Data Scientist
