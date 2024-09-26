# Finance Data Capstone Project

## Project Overview
This project performs an Exploratory Data Analysis (EDA) of bank stocks during the financial crisis period, from January 1st, 2006 to January 1st, 2016. The analysis focuses on data visualization techniques to explore patterns and trends in stock prices.

This is the second capstone project from the Udemy course: Python for Data Science and Machine Learning Bootcamp. The primary objective of this notebook is to provide educational insights into stock price movements without offering any financial advice.

Disclaimer: The observations made in this analysis are not financial recommendations. Past performance of stocks does not guarantee future performance.


## Introduction and Objective

The analysis aims to understand the trends in bank stocks during the financial crisis.

## Data Collection

Bank stock data was collected, including well-known banks such as JPMorgan Chase, Wells Fargo, and Goldman Sachs.
The data includes daily stock prices over the selected 10-year period.

## Data Preprocessing

Missing data, data types, and other necessary checks were handled before proceeding to the analysis.
## Exploratory Data Analysis (EDA)

- Stock Price Trends: Visualization of the stock price movements for different banks.
- Correlation Matrix: An analysis of the correlation between different bank stock prices.
- Moving Averages: A comparison of different moving averages for each bank’s stock price to understand trends.
- Stock Returns: Analysis of the returns of each bank during the financial crisis.

## Data Visualization

Extensive use of libraries like matplotlib, seaborn, and plotly to create informative visualizations.

Some key visualizations include:
- Stock price trends over time for various banks.
- Correlation heatmaps showing relationships between the banks' stock prices.
- Volatility and daily returns during significant financial events.
Key Insights
- Comparison of stock performances during key financial events.
Volatility insights and patterns during and after the financial crisis.

## Approach

- Descriptive Statistics: Basic statistical measures like mean, median, and standard deviation of stock prices were computed for each bank to understand general trends.
- Correlation Analysis: A heatmap was generated to show the correlation between different bank stock prices. This helps in understanding how different banks' stock movements are related.
- Moving Averages: Various moving averages (10-day, 50-day, and 200-day moving averages) were calculated for each bank to smooth out short-term fluctuations and identify longer-term trends.
- Daily Returns: Returns were calculated as the percentage change in stock price between consecutive days. This provided insights into the volatility of each stock.

## Models and Advanced Techniques

- Volatility Analysis: To gauge the risk associated with each stock, rolling volatility (standard deviation of stock returns over a specific period) was computed.
- Pairplot and Jointplot: Pairplots and jointplots were generated to observe relationships between stocks and their returns. This visually highlighted relationships and trends in stock movements across different banks.
- Risk-Return Tradeoff: The risk-return tradeoff was analyzed by comparing each stock's average daily returns with its volatility during the period.
- Cumulative Return: The cumulative return for each bank stock was calculated to visualize the total change in stock price over time, which helped identify the overall performance of each bank during the financial crisis.

## Results and Key Insights
1) Correlation Between Bank Stocks
The correlation matrix and heatmap revealed strong positive correlations between most bank stocks. This indicated that stock prices for the major banks generally moved in tandem during the financial crisis.

2) High Volatility During the Crisis
Rolling volatility graphs showed heightened volatility for all bank stocks during key moments of the financial crisis. This was expected, as stock prices were more volatile in times of financial instability.

3) Bank Performances
The cumulative return analysis revealed significant variations in the performance of different banks. For example, some banks showed a strong recovery in the post-crisis period, while others struggled for an extended period.

4) Risk-Return Tradeoff
Analysis of the risk-return tradeoff indicated that certain banks had higher volatility, yet did not provide proportionally higher returns. This finding would be crucial for investors when assessing the riskiness of each bank stock.

5) Key Financial Events Impact
The stock prices and volatility graphs showed major dips around key events like the Lehman Brothers collapse and other financial institutions' bailouts. These events clearly had a profound impact on the banking sector during this period.