{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Project Summary\
\
## Trader Performance vs Market Sentiment Analysis\
\
### Objective\
\
The objective of this project was to investigate the relationship between Bitcoin market sentiment and trader performance on the Hyperliquid platform. The analysis aimed to understand whether different market sentiment conditions influence trader profitability, trading activity, and overall behavior.\
\
---\
\
## Methodology\
\
The analysis began by loading the Bitcoin Fear & Greed Index and Hyperliquid historical trading datasets into Python.\
\
The data was cleaned by handling missing values, checking for duplicates, standardizing column names, and converting timestamps into a common daily format. Both datasets were then merged using the Date column.\
\
Several performance metrics were created, including:\
\
- Daily Profit and Loss (PnL)\
- Win/Loss Indicator\
- Win Rate\
- Average Trade Size\
- Number of Trades Per Day\
\
Exploratory Data Analysis (EDA) was performed using summary statistics and visualizations to compare trader performance under different market sentiment conditions.\
\
---\
\
## Key Findings\
\
- Trader performance varies across different market sentiment categories.\
- Market sentiment influences trading activity and trade sizes.\
- Win rates differ between Fear and Greed market conditions.\
- Frequent traders demonstrate different performance characteristics compared to infrequent traders.\
- Market sentiment can provide valuable context for understanding trader behavior.\
\
---\
\
## Recommendations\
\
Based on the analysis, the following recommendations are proposed:\
\
1. Incorporate market sentiment into trading decisions by applying more conservative risk management during Fear and Extreme Fear periods.\
\
2. Combine historical trader performance with market sentiment before increasing trade frequency or position sizes to improve decision-making.\
\
---\
\
## Conclusion\
\
This project demonstrates that Bitcoin market sentiment is associated with measurable differences in trader behavior and performance. While sentiment alone should not determine trading decisions, combining sentiment indicators with historical trading metrics can support better risk management and more informed trading strategies.}