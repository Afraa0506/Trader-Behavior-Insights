# Trader-Behavior-Insights
This notebook analyzes the behavior and performance of crypto traders during different market sentiments — from Extreme Fear to Extreme Greed — by merging historical trading data with the Bitcoin Fear & Greed Index. Through visualizations and statistical summaries, the project uncovers how trader profits, volume, and coin-wise performance shift with market mood. Ideal for those interested in Web3 analytics, behavioral finance, or data-driven trading strategies.

## Objective

This project explores the relationship between **market sentiment** (Fear, Greed, etc.) and **trader performance** using real-world trading data from Hyperliquid and a Bitcoin Fear & Greed index.

##  Datasets Used

1. **Fear & Greed Index**
   - Columns: `Date`, `Classification` (e.g., Fear, Greed, Neutral, etc.)
   - [Fear & Greed Index Dataset](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view)

2. **Historical Trader Data**
   - Key columns: `Timestamp IST`, `Coin`, `Size USD`, `Closed PnL`, `Side`, `Account`, etc.
   - [Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view)

##  Analysis Performed

- Merged both datasets on date to align sentiment with trade activity.
- Analyzed:
  - Average **Closed PnL** by sentiment
  - Total **Trading Volume** (USD) by sentiment
  - Coin-wise performance under different sentiment types
- Visualized insights using bar charts, box plots, and heatmaps.

##  Key Insights

- **Greed days** yielded higher average profits compared to Extreme Greed days — indicating more controlled optimism leads to better trading outcomes.
- **Fear days** had the **highest trading volume**, showing heightened market activity during uncertain conditions.
- Coins like **@107** and **kPEPE** showed strong sentiment sensitivity, while others like `kSHIB` performed more steadily.
- Extreme sentiment days (Extreme Fear/Greed) saw more **volatility and inconsistent performance**.

##  Tools & Libraries

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

##  Conclusion

Market sentiment has a strong influence on trading behavior and profitability. Understanding these dynamics can help traders and analysts develop **sentiment-aware trading strategies** in crypto markets.

##  How to Run

1. Clone the repo or download the `.ipynb` file.
2. Run all cells in Jupyter Notebook.
3. Make sure both CSV files (`trades.csv` and `sentiment.csv`) are in the same directory.

---

## Author

**Afraa Sulaiha S**  
*UG Student | AI & Data Science Enthusiast*
