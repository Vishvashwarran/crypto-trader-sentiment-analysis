Trader Behavior Analysis Using Bitcoin Market Sentiment
Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance. By combining the Fear & Greed Index with historical trader activity from Hyperliquid, the analysis explores how market emotions influence trading behavior, profitability, and risk-taking patterns.

The goal is to uncover insights that can help traders and analysts design smarter trading strategies and better understand how sentiment-driven markets affect performance.

Objectives

Analyze how trader profitability changes during Fear and Greed market conditions.

Examine trading volume and behavior across different sentiment levels.

Identify patterns in trader performance based on market sentiment.

Highlight top-performing traders and analyze their impact.

Datasets Used
1. Bitcoin Fear & Greed Index

Contains daily sentiment classification of the Bitcoin market.

Columns include:

Date

Value (Sentiment score)

Classification (Extreme Fear, Fear, Greed, Extreme Greed)

2. Hyperliquid Historical Trader Data

Contains transaction-level trading activity.

Columns include:

Account

Coin

Execution Price

Size Tokens

Size USD

Side (Buy/Sell)

Timestamp

Start Position

Direction

Closed PnL

Transaction Hash

Fee

Trade ID

Tools and Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Data Processing Steps

Load both datasets using Pandas.

Convert timestamps to proper datetime format.

Extract date information from trade timestamps.

Merge trader data with market sentiment data using date.

Perform exploratory data analysis (EDA).

Visualize relationships between sentiment and trading behavior.

Generate insights about trader performance.

Key Analysis Performed

Average trader profit during Fear vs Greed periods

Trading volume analysis by sentiment

Buy vs Sell activity during different market sentiments

Identification of top-performing traders

Correlation analysis between market sentiment score and trader profit

Key Insights

Trading activity tends to increase during Greed periods, suggesting traders are more confident in bullish markets.

Trader profitability is generally higher during Greed sentiment periods compared to Fear periods.

Fear markets show higher volatility and inconsistent trading results due to uncertainty.

A small group of traders consistently generate high profits regardless of market sentiment.

Conclusion

The analysis demonstrates that Bitcoin market sentiment has a measurable influence on trader behavior and performance. Greed periods typically encourage higher trading activity and larger positions, while Fear periods introduce increased volatility and inconsistent profits.

Understanding these sentiment-driven patterns can help traders improve their strategies, manage risk more effectively, and make more informed decisions in cryptocurrency markets.

Future Improvements

Future work could include:

Analyzing leverage usage across sentiment conditions

Identifying behavioral patterns of consistently profitable traders

Applying machine learning models to predict trader success

Studying long-term trader performance trends
