# Trader Performance vs Market Sentiment Analysis

## 📌 Overview
This project explores the relationship between **trader performance** (from Hyperliquid historical data) and **Bitcoin market sentiment** (Fear/Greed Index). The goal is to uncover hidden patterns and deliver insights that can guide smarter trading strategies in Web3 trading.

---

## 📂 Datasets
1. **Historical Trader Data (historical_data.csv)**
   - Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Closed PnL`, `Fee`, etc.

2. **Bitcoin Market Sentiment (fear_greed_index.csv)**
   - Columns: `timestamp`, `value`, `classification`, `date`

---

## 🛠️ Methodology
1. **Data Preparation**
   - Convert timestamps to proper datetime format
   - Create a common `Date` column for merging
   - Clean and align datasets

2. **Exploratory Data Analysis (EDA)**
   - Average PnL under different sentiment categories
   - Leverage distribution across Fear/Greed
   - Trade side counts (BUY vs SELL)
   - Correlation matrix of trader metrics

3. **Pattern Discovery**
   - Win/loss ratios by sentiment
   - Trade volume trends under Fear vs Greed
   - Hidden correlations between execution price, trade size, and PnL

4. **Visualization**
   - Bar plots, box plots, count plots, and heatmaps to illustrate findings

---

## 📊 Key Insights
- Traders tend to perform differently under **Fear vs Greed** conditions.
- **Extreme Fear** phases show lower win rates and higher volatility.
- **Greed phases** often yield higher average PnL, but leverage discipline is critical.
- Trade direction (BUY vs SELL) aligns with sentiment shifts.
- Correlation analysis highlights links between execution price, trade size, and profitability.

---

## ✅ Recommendations
Traders should adapt strategies based on sentiment signals. In **Extreme Fear**, reduce position sizes and leverage to preserve capital. During **Greed phases**, profits may rise but discipline is key—moderate leverage and timely exits help avoid sudden losses. SELL positions often perform better in fearful markets, while BUY positions dominate in greedy ones. Monitoring trade volumes can reveal crowd behavior, where contrarian approaches may be safer. Overall, integrating sentiment data into trading decisions and reassessing strategies regularly ensures resilience against shifting market psychology.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
  https://github.com/Risharma2727/PrimetradeAI-Internship-Assignment



## Install dependencies:
  pip install pandas matplotlib seaborn
  
## Run the Jupyter Notebook:
  jupyter notebook analysis.ipynb
