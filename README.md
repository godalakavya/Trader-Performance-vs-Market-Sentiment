# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance on the Hyperliquid platform. By combining the Bitcoin Fear & Greed Index with historical trading data, the analysis explores how market sentiment influences trading behavior, profitability, trade frequency, and risk-taking patterns.

The project aims to identify meaningful trends and provide actionable trading recommendations based on data-driven insights.

---

## Objective

The objective of this project is to:

- Analyze the relationship between Bitcoin market sentiment and trader performance.
- Measure the impact of Fear, Greed, Neutral, Extreme Fear, and Extreme Greed market conditions on trading outcomes.
- Evaluate changes in trader behavior across different market sentiments.
- Generate actionable strategy recommendations based on the findings.

---

## Dataset Information


### 1. Bitcoin Market Sentiment Dataset

**Columns Used**
- Date
- Classification (Fear, Greed, Neutral, Extreme Fear, Extreme Greed)
- https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

### 2. Hyperliquid Historical Trader Dataset

"Due to dataset size/licensing, the historical trader dataset is not included. It can be downloaded from the link provided in the assignment."

https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
**Columns Used**
- Account
- Coin
- Execution Price
- Size USD
- Size Tokens
- Side
- Timestamp IST
- Closed PnL
- Fee
- Direction

---

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

---

## Methodology

The project followed these steps:

1. Loaded both datasets into Python.
2. Performed data exploration and quality checks.
3. Checked missing values and duplicates.
4. Converted timestamps into daily dates.
5. Merged trader data with the Fear & Greed Index using the Date column.
6. Engineered new features such as:
   - Daily PnL
   - Win/Loss Indicator
   - Win Rate
   - Average Trade Size
   - Trades Per Day
7. Segmented traders into Frequent and Infrequent groups.
8. Conducted exploratory data analysis using charts and summary statistics.
9. Interpreted findings and proposed trading strategies.

---

## Key Metrics

The following metrics were analyzed:

- Average Closed PnL
- Daily PnL per Trader
- Win Rate
- Average Trade Size
- Number of Trades Per Day
- Long vs Short Distribution
- Trader Segmentation
- Sentiment Distribution

---

## Key Insights

- Trader profitability varies across different market sentiment categories.
- Trading activity changes depending on market sentiment.
- Average trade size differs under Fear and Greed market conditions.
- Frequent traders exhibit different performance characteristics compared to infrequent traders.
- Market sentiment provides useful context for understanding trading behavior and performance.

---

## Strategy Recommendations

**Recommendation 1**

Use market sentiment as an additional risk management indicator. During Fear or Extreme Fear periods, traders may consider reducing position sizes or using more conservative leverage.

**Recommendation 2**

Monitor historical trader performance alongside market sentiment before increasing trading activity, particularly during highly optimistic or highly pessimistic market conditions.

---

## Project Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── Trader_Performance_vs_Market_Sentiment_Analysis.ipynb
├── README.md
├── Project_Summary.md
├── requirements.txt
└── outputs/
```

---

## How to Run

1. Clone the repository.

```
git clone <repository-link>
```

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the notebook.

```
jupyter notebook
```

4. Run all cells sequentially to reproduce the analysis.

---

## Future Improvements

Possible future enhancements include:

- Building a predictive model for trader profitability.
- Clustering traders into behavioral archetypes.
- Developing an interactive dashboard using Streamlit.
- Incorporating additional market indicators such as volatility and trading volume.
- Performing time-series forecasting for trader performance.

---

## Author

**Kavya**

Data Analytics | Data Science | Python | SQL | Machine Learning
