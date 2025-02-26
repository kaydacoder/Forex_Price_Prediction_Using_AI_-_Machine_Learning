# Forex Price Prediction Using AI & Machine Learning

## Why It Stands Out:
- ✅ Goes beyond basic time-series forecasting by integrating NLP (spaCy) to analyze market sentiment from financial news.
- ✅ Helps traders predict currency price movements using historical data, news sentiment, and machine learning.
- ✅ Combines Pandas, Seaborn, NLP (spaCy), and Machine Learning for a holistic approach.

## How to Execute:

### 1. Dataset Collection:
- **Historical Forex Data**: Get currency pair data (e.g., EUR/USD, GBP/USD) from Yahoo Finance or Alpha Vantage.
- **News Sentiment Data**: Scrape financial news articles & Forex-related tweets using web scraping (BeautifulSoup, Tweepy).

### 2. Data Preprocessing (Pandas & NLP - spaCy):
- Clean and format Forex price data (handling missing values, converting timestamps).
- Use spaCy to process financial news headlines:
  - Tokenization, stopword removal, Named Entity Recognition (NER).
- Extract sentiment scores using VADER or TextBlob.
- Merge news sentiment scores with Forex price data based on timestamps.

### 3. Exploratory Data Analysis (Seaborn):
- Visualize currency trends over time (candlestick charts, line plots).
- Correlate news sentiment with Forex price movements.
- Heatmaps to analyze volatility patterns across different currency pairs.

### 4. Machine Learning Model:
- **Feature Engineering**: Combine historical price movements, technical indicators (RSI, MACD), and sentiment scores.
- **Model Selection**:
  - Use LSTM (Long Short-Term Memory) for deep learning-based time-series forecasting.
  - Compare with traditional models like XGBoost or ARIMA.
- Train the model on past data and validate with recent price trends.

## Final Deliverable:
🚀 An interactive Python-based tool where users can:
- Input a currency pair (e.g., EUR/USD).
- See predicted price trends for the next X days based on AI analysis.
- View live sentiment analysis of Forex-related news.

## Why It Impresses Employers:
- 🔥 Bridges AI with real-world finance applications.
- 📈 Combines quantitative finance with NLP & deep learning.
- 💡 Aligns with algo-trading, fintech, and investment tech trends.

Would you like code snippets to get started? 🚀
