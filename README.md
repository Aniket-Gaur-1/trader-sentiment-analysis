# Trader Performance vs Market Sentiment (Primetrade.ai Assignment)

## Overview
This project analyzes how Bitcoin market sentiment (Fear/Greed Index) impacts trader behavior and performance on Hyperliquid. The goal is to uncover behavioral patterns that can inform better trading strategies.

## Datasets
- Bitcoin Fear & Greed Index (daily sentiment)
- Hyperliquid historical trader execution data

## Methodology
1. Cleaned and standardized both datasets
2. Converted timestamps and aligned by date
3. Aggregated trader metrics daily:
   - Total PnL
   - Win rate
   - Average trade size
   - Leverage
   - Trade count
   - Long/short ratio
4. Compared metrics across Fear vs Greed sentiment regimes
5. Built a Random Forest classifier to predict next-day profitability using trader behavior features

## How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn

2. Open notebook.ipynb in Jupyter and run all cells top to bottom.

## Key Findings
See report.md for insights and strategy recommendations.
