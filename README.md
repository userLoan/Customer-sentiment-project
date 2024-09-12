# Customer-sentiment-project
Can we use Sentiment Analysis to Predict Stock Prices?

# OVERVIEW

This project explores the potential of using sentiment analysis to understand the relationship between financial news sentiment and the movements in company stock prices. This project combined web scraping, natural language processing, and financial data analysis to provide insights into market trends and investor sentiment.

## Goal of this notebook: 
* Assess the impact of financial news sentiment on stock prices.
* Generate visual reports and analytics to better understand the correlation between news and stock price movements.

## The analysis consists of three steps:
* PART A: Data Collection
* PART B: Data Visualization
* PART C: Sentiment Analysis

### PART A
* Utilized PRAW to scrape relevant posts from Reddit's r/stocks subreddit
* Fetched historical stock data using the yfinance library
* Focused on major finance companies, with JPM (JPMorgan Chase) as the primary case study

### PART B
#### 1. Stock prices
* Created time series visualizations of stock prices for major finance companies
* Implemented interactive charts for better data exploration
  
![image](https://github.com/user-attachments/assets/a17711de-ee6b-4e11-a260-7b2ea7b9d1b6)

#### 2. Sentiment
* Implemented sentiment analysis on Reddit posts using TextBlob
* Calculated daily average sentiment scores
* Visualized sentiment distribution using histograms
  
![image](https://github.com/user-attachments/assets/8b4cd662-889b-4463-bd3b-acc10a6c7c33)

Sentiment distribution was roughly bell-shaped with a slight positive skew, ranging from -0.4 to 0.8, with most scores between 0 and 0.2

### PART C 
* Synchronized Reddit sentiment data with corresponding stock prices
* Time series plots of sentiment vs. stock prices

![image](https://github.com/user-attachments/assets/a567e42f-000a-4e1e-b590-0b771d7c9612)

# Data Insights

Emotions drive customer behavior, sentiment analysis on customer feedback forms a tool for driving improvement in customer sentiment, customer behavior, and the business itself.

In this case:
1. Correlation Analysis

The correlation coefficient between sentiment and closing price is -0.15, indicating a weak negative correlation.

=> Suggests a complex, non-straightforward relationship between public sentiment and stock prices for large corporations

2. Stock Price Trends vs Sentiment Volatility
* The stock price (orange line) shows a clear upward trend over time, particularly accelerating from 2020 onwards.
* Sentiment scores (blue line) are highly volatile, with frequent and sharp fluctuations.

## Key Takeaways
* The relationship between public sentiment and stock prices for major corporations is complex and not straightforward.
* As one of the largest banks in the world, JPMorgan Chase's stock tends to be more stable due to its large market capitalization.
* Social media sentiment alone may not be a strong predictor of stock performance for large financial institutions. A comprehensive market analysis should combine sentiment data with other financial and macroeconomic indicators.

THE END.









  
