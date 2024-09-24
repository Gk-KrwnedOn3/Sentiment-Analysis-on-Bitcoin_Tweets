
# Sentiment-Analysis-on-BItcoin-tweets
This project performs sentiment analysis on tweets related to Bitcoin using both the TextBlob and VADER sentiment analysis approaches. The dataset consists of tweets from 01/01/2022 to 22/06/2023, and the analysis aims to examine how public sentiment about Bitcoin correlates with Bitcoin price changes with visualizations of data.

# Project Overview
This project performs sentiment analysis on Bitcoin-related tweets from 01/01/2022 to 22/06/2023 using two sentiment analysis techniques: TextBlob and VADER. The primary goal is to understand how public sentiment correlates with the fluctuations in Bitcoin prices during the same period.

# Features
Sentiment Analysis: Classifies tweets into positive, negative, or neutral sentiment using both TextBlob and VADER sentiment analysis tools.
Bitcoin Price Correlation: Compares the daily sentiment scores with Bitcoin’s daily closing prices.
Data Visualizations:
Doughnut chart showing sentiment percentages (positive, negative, neutral).
Word cloud of hashtags used in the tweets.
Monthly bar chart displaying the total number of positive, negative, and neutral sentiments.
Line plot correlating Bitcoin prices with sentiment scores (from both TextBlob and VADER).

# Setup
Download all the files(scripts and csv) and compile them into a folder. Load the folders in Jupyter Notebook, you could use Anaconda Navigator to access Jupyter notebook or carry on with ways you deemed comfortable
Important scripts are EDA.ipynb and Sentimet.ipynb

# Usage
1. Exploratory Data Analysis (EDA)
In the eda.ipynb notebook, you will:

Load and explore the dataset, including initial data cleaning and inspection.
Perform basic statistics and visualizations to understand the data structure.
To start EDA:

Open the eda.ipynb notebook in Jupyter.
Run the cells sequentially to explore and clean the tweet and Bitcoin datasets.

2. Sentiment Analysis & Correlation
In the sentiment.ipynb notebook, you will:

Load the pre-processed sentiment analysis data (tweets_with_textblob_sentiment.csv and tweets_with_vader_sentiment.csv).
Visualize sentiment distribution using:
Doughnut chart: Shows the percentage of positive, negative, and neutral sentiments.
Word cloud: Displays hashtags from the tweets.
Bar chart: Presents monthly sentiment totals (positive, negative, neutral).
Bitcoin sentiment correlation: Compares Bitcoin price changes with daily average sentiment scores from TextBlob and VADER.
To perform sentiment analysis and visualize results:

Open the sentiment.ipynb notebook.
Run the cells to perform sentiment analysis, plot charts, and compare sentiment with Bitcoin prices.

# Visualizations
Sentiment Percentage (Doughnut Chart)

Word Cloud of Hashtags

Monthly Sentiment Distribution (Bar Chart)

Bitcoin Price vs Sentiment Correlation

# Future Work
Expand the dataset: Include more recent tweets to analyze ongoing trends.
Deeper sentiment models: Implement more advanced sentiment analysis techniques like BERT or GPT.
Time Series Analysis: Perform time series forecasting on Bitcoin prices using public sentiment as a predictive factor.
