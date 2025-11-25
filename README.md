# Financial News and Stock Analysis (Week 1)

This repository contains the code, analysis, and findings for **Week 1** of the Financial News and Stock Price Integration project. The goal of this week was to explore, analyze, and integrate financial news data with stock price data to understand trends, compute technical indicators, and examine correlations between news sentiment and stock movements.



## **Project Overview**

### **Task 1: Exploratory Data Analysis (EDA)**
- Performed descriptive statistics on news headlines:
  - Headline length distribution
  - Number of articles per publisher
  - Time-based analysis of article publishing
- Conducted text analysis using **NLTK**:
  - Tokenized headlines
  - Removed stopwords
  - Generated top keywords and a **WordCloud**
- Key Insights:
  - Headlines are concise, often 8–15 words
  - A few publishers dominate the financial news feed
  - Most articles are published in the morning hours

### **Task 2: Quantitative Stock Analysis**
- Loaded stock price data including **Open, High, Low, Close, Volume**
- Applied technical indicators using **TA-Lib**:
  - SMA (20-day, 50-day)
  - EMA (20-day, 50-day)
  - RSI (14-day)
  - MACD
- Visualized stock trends, momentum, and trading signals
- Key Insights:
  - Moving averages help smooth price trends
  - MACD crossovers indicate potential trend reversals
  - RSI highlights overbought/oversold conditions

### **Task 3: News-Sentiment and Stock Correlation**
- Aligned news and stock data by dates
- Applied sentiment analysis on headlines using **VADER**
- Computed daily stock returns
- Merged daily sentiment scores with stock returns
- Calculated correlation between news sentiment and stock movements
- Key Insights:
  - Weak positive correlation between sentiment and daily returns
  - Shifting post-market headlines to next trading day improves alignment
