# 📊 Market Sentiment & Trader Performance Analysis

> **Internship Data Science Task – by Devansh Srivastava**

This project analyzes how the **Fear & Greed Index** affects **trader behavior and performance** in crypto markets, using real trade-level data from the Hyperliquid platform.

---

## 📁 Dataset Overview

1. `historical_data.csv`  
   ⤷ Contains trade details like timestamp, coin, side (BUY/SELL), size, PnL, etc.

2. `sentiment.csv`  
   ⤷ Daily sentiment scores (0 = Extreme Fear, 100 = Extreme Greed)

---

## 📂 Dataset Download Links

Due to GitHub's upload size limit, the raw datasets are hosted on Google Drive:

- 🔗 [historical_data.csv (45MB)](https://drive.google.com/uc?export=download&id=YOUR_FILE_ID_HERE)
- 🔗 [fear_greed_index.csv](https://drive.google.com/uc?export=download&id=YOUR_FILE_ID_HERE)

---

## 🛠️ Project Steps

- Cleaned and pre-processed both datasets
- Merged them on date to align trade and sentiment data
- Created new columns (USD Size, Time, Classification etc.)
- Generated 6 visualizations to uncover patterns

---

## 📊 Visualizations & Insights

| 📈 Plot | 📌 Description |
|--------|----------------|
| `fear_greed_score_timeseries.png` | How market sentiment changed over time |
| `pnl_vs_sentiment.png` | Profit/Loss distribution during different sentiments |
| `side_sentiment_count.png` | Buy vs Sell behavior during Fear, Greed, and Neutral |
| `top_coins_sentiment.png` | Top 10 most traded coins across sentiments |
| `trade_size_vs_sentiment.png` | Trade size distribution in Fear vs Greed |
| `top_traders_pnl_sentiment.png` | How top traders performed under different market moods |

All visuals are stored in the `outputs/` folder.

---

## 💡 Key Takeaways

- Fear periods are volatile but also profitable for some
- Greed triggers higher risk-taking (bigger trades, meme coins)
- Top traders stay profitable regardless of sentiment

---

## 🔍 Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **Jupyter Notebook**
- **Data Visualization** using both static and interactive libraries

---

## 👤 About Me

**Devansh Srivastava**  
B.Com, Kirori Mal College  
Aspiring Data Scientist | Python Developer | Crypto Enthusiast  

🔗 [LinkedIn](https://www.linkedin.com/in/connectwithdevansh/)  
💻 [GitHub](https://github.com/dsrivastava-py?tab=repositories)  
📧 devanshsrivastava.reads@gmail.com  

---

## ✅ What's Included

- ✅ Cleaned and merged datasets
- ✅ Python scripts/notebooks
- ✅ 6 well-labelled charts
- ✅ Final Report (`PDF-ready`)
- ✅ This `README.md`

---

## ⚠️ Note

👉 Datasets are too large for GitHub upload, so they’ve been hosted on Google Drive for easy access and reproducibility.

All data used is anonymized and for educational/demo purposes only.  
The project was built as part of a Data Science internship assignment.

---
