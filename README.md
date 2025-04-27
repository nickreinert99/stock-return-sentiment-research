# Stock Sentiment and Return Analysis

This repository contains code analyzing stock returns and market news sentiment using Python.  
The project involves fetching historical stock data, calculating log returns, aggregating sentiment scores from financial news sources, and saving the processed data.
In addition to sentiment analysis across different lag periods to account for sentiment buildup over time, the project uses this analysis along with other financial metrics
as features for a logistic regression model to predict stock movements.  
Finally, an efficient frontier and optimal portfolio are constructed from 24 stocks categorized by market capitalization.

## Technologies Used
- Python
- Pandas
- NumPy
- Alpha Vantage API

## Note
- API keys are required to fetch data (not included for security reasons).
