# Primetrade_Intern_Assignment
A Data Science study analyzing the correlation between Hyperliquid trader performance and Bitcoin Market Sentiment (Fear/Greed).
# 📊 Trader Performance vs. Market Sentiment Analysis
This project explores the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and trading performance on the Hyperliquid exchange.

## 🛠 1. Methodology
- **Data Merging:** Combined daily Fear & Greed Index values with individual trade logs using Python/Pandas.
- **Cleaning:** Standardized timestamps and converted PnL values to a base currency for consistent comparison.
- **Categorization:** Grouped trades into 'Small' and 'Big' segments to analyze risk behavior across different sentiment cycles.

## 📈 2. Key Insights
- **The FOMO Effect:** During 'Greed' periods, average trade sizes increase, but Win Rates decrease, suggesting emotional "chasing" of the market.
- **Fear Performance:** Win rates are statistically higher during 'Fear' days, indicating that the trader is more selective and disciplined when sentiment is low.
- **Volatility:** 'Greed' cycles show wider PnL swings, increasing the risk of significant account drawdowns.

## 💡 3. Strategy Recommendations
- **Leverage Scaling:** Automatically reduce maximum leverage by 25% when the Fear & Greed Index is above 70.
- **Position Sizing:** Prioritize "Small Trade" setups during Fear cycles to capitalize on higher win-rate environments with lower emotional stress.
