
# Twitter Sentiment Trading Strategy

This project implements a trading strategy based on sentiment analysis of Twitter data. The strategy aims to leverage public sentiment towards specific stocks to make informed trading decisions. The project is built using Python and various data analysis libraries.

## Introduction
The Twitter Sentiment Trading Strategy project utilizes sentiment analysis on tweets to predict stock movements. By analyzing public sentiment, the strategy attempts to buy or sell stocks based on the perceived positive or negative sentiments.

## Dependencies
The following libraries are required to run the project:
- pandas
- numpy
- tweepy
- textblob
- sklearn
- matplotlib

## How It Works
1. **Data Collection**: The project uses the Tweepy library to collect tweets related to specific stocks.
2. **Sentiment Analysis**: The TextBlob library analyzes the sentiment of each tweet, classifying it as positive, negative, or neutral.
3. **Trading Strategy**: The strategy uses sentiment scores to make buy or sell decisions for the selected stocks.
4. **Visualization**: The results are visualized using Matplotlib to show the performance of the trading strategy.
