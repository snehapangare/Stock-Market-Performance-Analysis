# Stock-Market-Performance-Analysis
Given historical stock price data for Apple, Microsoft, Netflix and Google over the past three months, your task is to analyze and compare the performance of these companies in the stock market using various data science techniques. Specifically, the goal is to identify trends and patterns in stock price movements, calculate moving averages and volatility for each company, and conduct correlation analysis to examine the relationships between different stock prices.
import plotly.express as px
fig = px.line(df, x='Date', 
              y='Close', 
              color='Ticker', 
              title="Stock Market Performance for the Last 3 Months")
fig.show()
