# Web3 Trading Data Science Assignment

## Candidate
**Name:** NikhilTej Pathakota  
**Role Applied:** Data Science – Web3 Trading Team  

---

## 📌 Project Overview
This project analyzes the relationship between trader behavior and overall market sentiment in cryptocurrency markets. By combining historical trader data from Hyperliquid with the Bitcoin Fear & Greed Index, the analysis explores how profitability, trading volume, win rate, and directional bias vary across different sentiment regimes.

The objective is to identify behavioral patterns and actionable insights that can inform smarter, sentiment-aware trading strategies in Web3 markets.

---

## 📂 Dataset Sources
1. **Historical Trader Data (Hyperliquid):**  
   https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

2. **Bitcoin Fear & Greed Index:**  
   https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

---

## 📁 Project Structure
ds_nikhiltej_pathakota/
├── notebook_1.ipynb
├── notebook_2.ipynb (optional)
├── csv_files/
│ ├── historical_data.csv
│ ├── fear_greed_index.csv
│ ├── daily_trader_metrics.csv
│ ├── merged_data.csv
│ └── sentiment_summary.csv (optional)
├── outputs/
│ ├── pnl_vs_sentiment.png
│ ├── volume_fear_greed.png
│ ├── winrate_sentiment.png
│ ├── long_short_ratio.png
│ └── correlation_heatmap.png
├── ds_report.pdf
└── README.md

## 🧠 Methodology Summary
- Cleaned and standardized historical trade data
- Engineered daily trader behavior metrics (PnL, volume, win rate, directional bias)
- Grouped sentiment into Fear, Greed, and Neutral categories
- Merged trader metrics with sentiment data at daily granularity
- Conducted exploratory data analysis and extracted actionable trading signals

---

## 📊 Key Insights
- Traders exhibit more disciplined behavior and higher win rates during Fear periods
- Greed periods show increased trading volume and stronger long bias
- Market sentiment influences trader behavior more strongly than direct profitability
- Sentiment-aware risk management improves trading stability

---

## ▶️ How to Run the Project

### Option 1: Google Colab (Recommended)
- Open `notebook_1.ipynb`
- Ensure access is set to **“Anyone with the link can view”**
- Upload CSV files or adjust paths accordingly

### Option 2: Local Execution
```python
pip install pandas numpy matplotlib seaborn
