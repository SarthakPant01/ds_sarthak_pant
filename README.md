# Trader Behavior vs Market Sentiment (Fear–Greed Analysis)

##  Overview
This project analyzes how **trader behavior and performance** change under different **market sentiment regimes (Fear vs Greed)** using real historical crypto trading data and the Bitcoin Fear–Greed Index.

The goal is to uncover behavioral and risk patterns that can inform **sentiment-aware trading strategies** in Web3 markets.

---

##  Objective
- Study the relationship between **market sentiment** and **trading outcomes**
- Compare profitability, volume, win rate, and risk during Fear vs Greed periods
- Extract actionable insights for better **risk management and position sizing**

---

##  Datasets
### 1. Historical Trader Data (Hyperliquid)
Trade-level data including:
- Execution price
- Trade size (tokens & USD)
- Buy / Sell side
- Closed PnL
- Fees
- Timestamps

### 2. Bitcoin Fear–Greed Index
Daily market sentiment classified as:
- Fear
- Greed

---

##  Methodology
1. **Data Cleaning & Preprocessing**
   - Normalized column names
   - Converted timestamps to datetime
   - Handled missing values
   - Filtered invalid trades

2. **Directional Analysis**
   - Buy vs Sell performance comparison

3. **Daily Aggregation**
   - Converted trade-level data into daily metrics:
     - Daily PnL
     - Trading volume
     - Trade count
     - Average fees

4. **Risk Metrics**
   - Cumulative PnL (Equity Curve)
   - Maximum Drawdown
   - Sharpe Ratio

5. **Sentiment-Based Analysis**
   - Merged daily trader metrics with Fear–Greed data
   - Compared behavior during Fear vs Greed regimes

---

##  Key Insights
- Trading performance is **more consistent and profitable during Greed**
- Fear periods show:
  - Higher volatility
  - Deeper drawdowns
  - Lower win rates
- Incorporating sentiment signals can significantly improve **risk-adjusted returns**

---

##  Project Structure

---

##  Tech Stack
- Python (Pandas, NumPy, Matplotlib)
- Google Colab
- GitHub

---

##  How to Run
1. Open `notebook_1.ipynb` in **Google Colab**
2. Upload the required CSV datasets
3. Run cells sequentially
4. Outputs and processed files will be saved automatically

---

##  Outcome
- Built an end-to-end analytics pipeline for trading behavior analysis
- Identified sentiment-driven performance and risk patterns
- Delivered insights aligned with real-world trading decision-making

---

## 👤 Author
**Sarthak Pant**  
