<<<<<<< HEAD
# Cryptocurrency Sentiment Analysis  

### Real-Time Cryptocurrency Price & Twitter Sentiment Correlation  

This project analyzes the relationship between **cryptocurrency price movements** and **Twitter sentiment** in real-time. The goal is to identify whether market sentiment on social media can act as a predictive signal for cryptocurrency price changes.  

---

## Project Overview  
- **Objective:** Explore the correlation between cryptocurrency prices (in USD) and Twitter sentiment scores.  
- **Approach:**  
  1. Collect real-time tweets about Bitcoin and other cryptocurrencies.  
  2. Perform **sentiment analysis** using VADER.  
  3. Compute a weighted sentiment score based on likes, followers, and tweet content.  
  4. Retrieve real-time cryptocurrency prices from the **Binance API**.  
  5. Perform **cross-correlation analysis** with different lag values to test predictive power.  
  6. Visualize correlations and trends in **real-time dashboards**.  

---

## Data Sources  
1. **Twitter API**  
   - Tweets containing crypto-related keywords (e.g., `bitcoin OR #BTC OR $BTC`).  
   - Extracted features:  
     - Tweet ID  
     - Text  
     - Username  
     - Followers count  
     - Retweets & likes  
     - Timestamp  

2. **Binance API**  
   - Cryptocurrency OHLCV (Open, High, Low, Close, Volume) data.  
   - 1-minute interval data for multiple assets:  
     - BTC, ADA, BCH, DOGE, SOL, USDT  

---

## ⚙️ Preprocessing  
- Removed links, tags, emojis, hashtags.  
- Filtered for **English-language tweets**.  
- Computed **compound sentiment score** using VADER.  
- Weighted tweets:  


---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/crypto-sentiment-analysis.git
   cd crypto-sentiment-analysis

2. Install dependencies:
    pip install -r requirements.txt

3. Run data collection:

    python src/collect_tweets.py
    python src/collect_crypto.py
=======
# CryptoPulse-Real-Time-Twitter-Sentiment-Price-Analysis
It is a Real-Time Twitter Sentiment &amp; Price Analysis.
>>>>>>> 5041e8f858c72f918f1f8161002a69276e31f34c
