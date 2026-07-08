# Trader Performance vs Market Sentiment

## Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data. The objective is to understand how market sentiment influences trader profitability, trading behavior, and decision-making.

---

## Dataset

This project uses two datasets:

- Bitcoin Fear & Greed Index
- Historical Trader Data (Hyperliquid)

**Note:** The datasets are not included in this repository as they were provided for the internship assignment.

---

## Methodology

The following steps were performed:

1. Loaded both datasets using Pandas.
2. Inspected the data structure, missing values, and duplicates.
3. Converted timestamps into date format.
4. Aligned both datasets by date.
5. Merged the datasets for analysis.
6. Performed exploratory data analysis (EDA).
7. Analyzed trader performance under different market sentiment conditions.
8. Segmented traders based on profitability, trading frequency, and consistency.

---

## Analysis Performed

### 1. Performance Analysis

- Average Closed PnL by Market Sentiment
- Win Rate by Market Sentiment
- Average Loss (Drawdown Proxy)

### 2. Trader Behavior Analysis

- Average Trade Size
- Number of Trades
- Long vs Short Position Distribution

### 3. Trader Segmentation

- Profitable vs Loss-Making Traders
- Frequent vs Infrequent Traders
- Consistent vs Inconsistent Winners

---

## Key Insights

- Traders achieved the highest average Closed PnL and win rate during **Extreme Greed** market conditions.
- **Extreme Fear** resulted in the largest average losses (Drawdown Proxy), indicating higher downside risk.
- Trading behavior changed across different market sentiment conditions, including trade size, trading frequency, and long/short positioning.
- Most traders were profitable overall, but only a small number were classified as **Consistent Winners**, highlighting the importance of maintaining consistent trading performance.

---

## Strategy Recommendations

- Apply stricter risk management and reduce leverage during **Extreme Fear** market conditions.
- Consider increasing position sizes only during strong bullish sentiment (**Extreme Greed**) while maintaining appropriate risk controls.
- Study the trading behavior of consistent winners to improve long-term trading performance instead of focusing only on short-term profits.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## How to Run

1. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib
```

2. Place the datasets in the project directory.

3. Open the Jupyter Notebook.

4. Run all cells sequentially.

---

## Project Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── Trader Performance vs Market Sentiment.ipynb
└── README.md
```

---

## Assignment

This project was completed as part of the **Primetrade.ai Data Science / Analytics Intern – Round-0 Assignment**.
