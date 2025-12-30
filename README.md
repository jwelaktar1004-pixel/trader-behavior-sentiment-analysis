# Trader Behavior vs Market Sentiment (Fear vs Greed)

## 📌 Project Overview
This project analyzes how trader performance varies under different Bitcoin market sentiment conditions (Fear vs Greed).  
The goal is to understand trading behavior, profitability, and risk distribution during different market moods.

---

## 📊 Datasets Used
- **Historical Trader Data (Hyperliquid)**
  - Trade-level data including execution price, size, side, leverage, and PnL
- **Bitcoin Fear & Greed Index**
  - Daily market sentiment classification

---

## 🛠️ Key Steps Performed
- Cleaned and standardized column names
- Fixed real-world timestamp issues (Unix epoch in seconds vs milliseconds)
- Aligned intraday trade data with daily sentiment
- Engineered features such as profitability flag and absolute trade size
- Performed exploratory data analysis (EDA)
- Visualized PnL distribution with and without outliers

---

## 🔍 Key Insights
- Fear periods show significantly higher trading activity and volatility
- Greed periods have fewer trades but higher average profitability driven by outliers
- Median PnL is close to zero, indicating most trades close near breakeven
- Market sentiment impacts risk distribution more than typical returns

---

## 📁 Files in this Repository
- `Trader_Sentiment_Analysis.ipynb` – Full analysis and code
- `Trader_Sentiment_Analysis_Report.pdf` – Executive summary report

---

## 🚀 Conclusion
Market sentiment plays a crucial role in shaping trader behavior.  
Fear markets encourage higher participation and volatility, while Greed markets favor selective, higher-reward trades.

---

## 👤 Author
**Jwel Aktar**  
Junior Data Scientist  
