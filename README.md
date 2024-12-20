# Stock Recommendation Enhancement Using OpenAI API, Sentiment Analysis, and Machine Learning

## Description

This project enhances stock recommendations for NASDAQ-100 companies by integrating sector classification, sentiment analysis of recent news articles, and stock price prediction from historical data. Using the OpenAI API, the project classifies companies by sector, analyzes news sentiment, and predicts future stock prices based on historical price data and current market trends. The goal is to offer informed stock recommendations based on year-to-date (YTD) performance.

## Features

-  **Sector Classification**: Automatically classify NASDAQ-100 companies into sectors using the OpenAI API.
-  **Stock Performance Analysis**: Analyze year-to-date (YTD) stock performance data.
-  **News Sentiment Analysis**: Fetch recent news articles for each company and analyze sentiment (positive, neutral, or negative).
-  **Stock Price Prediction**: Utilize historical stock price data to predict future stock prices using machine learning models.
-  **AI-Driven Recommendations**: Generate enhanced stock recommendations based on sector performance, news sentiment, and predicted stock price.
-  **Data Merging**: Combine company data and performance metrics to generate insights.

## Tools Used

- **Python 3.x**: Programming language
- **Jupyter Notebook**: Interactive development environment
- **OpenAI API**: For sector classification and generating insights
- **News API**: For fetching recent news articles
- **Scikit-learn**: For machine learning models, including stock price prediction
- **Pandas**: For data manipulation and analysis
- **Requests**: For making HTTP requests to APIs

## Setup Instructions

### 1. **Prerequisites**

Ensure you have the following installed:

- **Python 3.x**: Check by running `python --version`
- **Dependencies**: Install the required libraries using pip:

  ```bash
  pip install pandas openai requests
