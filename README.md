# Market Sentiment vs Trader Behavior

This project analyzes how market sentiment (Fear, Greed, Neutral) influences trader behavior using real-world datasets. It was created as part of a Data Science internship assignment for Primetrade.ai.

The analysis explores patterns in trading volume, profitability (PnL), and buy/sell behavior by aligning historical trade data with the Bitcoin Fear & Greed Index.

---

## 📁 Folder Structure

echo "ds_yash_yadav/"
echo "├── notebook_1.ipynb              # Main analysis in Google Colab"
echo "├── csv_files/"
echo "│   └── merged_trader_sentiment.csv  # Cleaned and merged dataset"
echo "├── outputs/"
echo "│   ├── volume_by_sentiment.png      # Barplot of trade volume"
echo "│   ├── avg_pnl_by_sentiment.png     # Barplot of average PnL"
echo "│   └── side_by_sentiment.png        # Buy/Sell comparison"
echo "└── ds_report.pdf                 # Final insights report with visuals"

---

## 📊 Key Findings

- 📈 **Volume:** Traders were most active during **Fear**, followed by **Greed**
- 💰 **Profitability:** Average PnL per trade was **highest in Fear** and lowest in Greed
- 🔄 **Trade Direction:**  
  - **More BUYs** occurred during Fear (dip-buying behavior)  
  - **More SELLs** occurred during Greed (profit-taking behavior)

These findings suggest that traders behave more cautiously and profitably during fearful market conditions.

---

## 🧠 Methodology

- Loaded and cleaned two datasets
- Merged on date for alignment
- Classified sentiment into `Fear`, `Greed`, and `Neutral`
- Performed exploratory data analysis (EDA)
- Visualized results using bar plots

---

## 🔧 Tools Used

- **Google Colab**
- **Python 3**
- **Libraries:** pandas, seaborn, matplotlib

---

## 🔗 Important Links

- 📓 [Google Colab Notebook](INSERT_YOUR_COLAB_LINK_HERE)
- 📁 [Dataset Source Links](provided in original assignment)

---

## 👤 Author

**Yash Yadav**  
_Data Science Intern Applicant – Primetrade.ai_  
📅 Date: 27/07/2025

---


