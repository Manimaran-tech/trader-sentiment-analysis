# 📊 Data Science Project – Market Sentiment vs Trader Behavior

## 🔍 Objective
This project explores how trader behavior (profitability, volume, fees) aligns with or diverges from market sentiment (Fear, Greed, etc.) using two datasets:

- **Fear & Greed Index**: Sentiment classification by date.
- **Historical Trader Data**: Transaction-level trading data from Hyperliquid.

## 📁 Project Structure
ds_manimaran/
├── notebook_1.ipynb # Main Colab notebook with analysis and plots
├── csv_files/ # Raw and cleaned CSV datasets
│ ├── fear_greed_index.csv
│ └── historical_data.csv
├── outputs/ # Plots and visual outputs
│ ├── avg_pnl_by_sentiment.png
│ ├── avg_fee_by_sentiment.png
│ ├── total_volume_by_sentiment.png
│ └── pnl_distribution_by_sentiment.png
├── ds_report.pdf # Final summarized insights and explanation
└── README.md # This file


## 🧹 Preprocessing Steps
- Converted timestamps to `datetime.date`
- Merged datasets on the `Date` column
- Selected key features: `Closed PnL`, `Size USD`, `Fee`, and `classification`

## 📊 Visualizations
1. **Average Profit/Loss by Sentiment**
2. **Total Trade Volume by Sentiment**
3. **PnL Distribution Histogram by Sentiment**
4. **Average Fee by Sentiment**

Plots are saved in the `outputs/` folder.

## ✅ How to Run
1. Open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive
3. Update dataset paths if needed
4. Run the notebook step-by-step

## 📌 Insights
- Traders are more active during **Extreme Greed**, but it doesn't always lead to higher profits.
- Fees and trade sizes vary significantly with market sentiment.
- Emotion-driven trading behavior is clearly evident.

## 🛠 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- Jupyter Notebook
- MS Word / PDF

---

