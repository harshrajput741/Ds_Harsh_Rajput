# 🧠 Data Science Assignment – Trader Behavior vs Market Sentiment  
### 📌 Submitted by: **Harsh Rajput**

This repository contains the complete solution for the Web3 Trading Team’s Data Science assignment.  
The goal of this project is to analyze how **trader behavior (risk, volume, leverage, PnL)** aligns or diverges from **Bitcoin market sentiment (Fear/Greed)**.

---

## 📂 Folder Structure
ds_Harsh_Rajput/
│
├── notebook_1.ipynb
├── ds_report_full.pdf
├── README.md
│
├── csv_files/
│ ├── fear_greed_index.csv
│ └── historical_data.csv
│
└── outputs/
├── merged_daily_metrics.csv
├── daily_aggregates.csv
├── grouped_by_sentiment.csv
├── fg_timeseries.png
├── daily_pnl_timeseries.png
├── daily_volume_timeseries.png
├── boxplot_pnl_by_sentiment.png
├── avg_leverage_by_sentiment.png
└── correlation_matrix.png


---

## 📘 Project Overview
We analyze:
- Bitcoin market sentiment (Fear vs Greed)
- Hyperliquid trader behavior (volume, leverage, pnl, buys/sells)
- Relationship between sentiment & trading actions
- Strategy-level insights based on data

---

## 🧹 Data Preprocessing
**Fear–Greed Dataset**
- Converted timestamps to dates
- Grouped by day
- Extracted final sentiment labels

**Trader Dataset**
- Converted “Timestamp IST” → datetime
- Cleaned numeric columns (Size USD, PnL, Leverage)
- Created daily aggregates (volume, trades, win-rate)

---

## 📊 Exploratory Data Analysis (EDA)
Generated all charts:
- Fear–Greed Index trend  
- Daily PnL  
- Daily Volume  
- PnL by sentiment boxplot  
- Avg leverage by sentiment  
- Correlation heatmap  

(Charts available in `/outputs/` folder)

---

## 🔍 Key Findings
- Greed days → HIGH volume & HIGH leverage  
- Fear days → LOW volume & LOW leverage  
- High leverage ≠ higher profit  
- Sentiment affects behavior but NOT profit predictability  

---

## 🚀 How to Use
**Colab:**  
- Open `notebook_1.ipynb`  
- Upload both CSVs  
- Run all cells  
- Outputs auto-generate

**Local:**  


pip install pandas numpy matplotlib


---

## 🙌 Author
**Harsh Rajput**  
Data Scientist
