# Trader Behavior vs Market Sentiment — Insights Report

## Objective
To understand how market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid.

## Methodology
Trader execution data was aggregated at account-day level and merged with Bitcoin Fear/Greed sentiment data. Metrics analyzed included daily PnL, win rate, leverage, trade frequency, position size, and long/short bias. A Random Forest classifier was trained to predict daily profitability using behavioral features.

## Key Insights

1. Traders perform better during Greed phases
Average daily PnL and win rates were higher on Greed and Extreme Greed days compared to Fear periods, suggesting risk-on market conditions favor profitable outcomes.

2. Leverage usage increases during Greed sentiment
Traders used higher average leverage on Greed days, while leverage dropped during Fear phases — indicating natural risk aversion behavior during uncertain markets.

3. Trade frequency rises during Fear periods but with lower efficiency
During Fear days, traders placed more trades but achieved lower win rates, suggesting overtrading or defensive positioning in volatile markets.

## Strategy Recommendations

1. During Fear markets:
Reduce leverage and trade selectively — high-frequency trading during Fear leads to lower profitability.

2. During Greed markets:
Allow higher leverage for historically profitable traders and increase trade participation selectively.

## Bonus: Predictive Modeling
A Random Forest classifier achieved ~83% accuracy in predicting daily trader profitability based on behavioral metrics, indicating sentiment + behavior features contain strong predictive signal.
