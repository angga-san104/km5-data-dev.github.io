Portfolio Optimization 
-------------------------

Metode : 
| Feature | Mean Variance | Hierarchical Risk Parity |
|----------|--------------|--------------------------|
| Objective | Return optimization | risk diversification |
| Risk diversification | Worse | Better |
| Market sensitivity (aset correlation) | More sensitive | Less sensitive |


Backtest :
| Feature | Walk Forward | Cross Validation |
|---------|--------------|------------------|
| Adaptability to changing conditions | Better | Less critical |
| Impact of short-term fluctuations | Less sensitive | More sensitive |
| Identification of long-term patterns | Essential | Less important |
| Overfitting risk | Lower | Higher |


**Investor Type**


| Feature	| Short Term | Long Term | Notes |
|---------|------------|-----------|-------|
| Objective |	Maximize expected return within a given risk tolerance |	Achieve equal risk contribution across assets	| MVO targets a specific risk level, while HRP focuses on proportional risk sharing |
| Risk Diversification | Lower | Higher| MVO may concentrate weight in high-return but high-risk assets, while HRP balances risk more evenly |
| Market Sensitivity | More sensitive to short-term market movements |	Less sensitive to short-term volatility | HRP aims to be less impacted by market fluctuations due to its focus on risk parity | 
| Adaptability to Changing Conditions |	More adaptable to changing market dynamics | Less adaptable to short-term changes	| MVO can quickly adjust weights based on new information, while HRP may be slower to react |
| Impact of Short-Term Fluctuations | Less impacted by short-term noise |	More impacted by short-term movements |	HRP's risk parity approach aims to smooth out the impact of short-term volatility |
| Identification of Long-Term Patterns | Less emphasis on long-term trends | More focus on identifying and capitalizing on long-term patterns | HRP's emphasis on risk parity might miss out on potential long-term trends in asset classes.
| Overfitting Risk |	Higher	| Lower	| MVO's reliance on historical data can lead to overfitting, while HRP's focus on risk parity is less susceptible |
| Backtesting Method	| Cross-validation	| Walk-forward	| Cross-validation tests the model on different data sets, while walk-forward tests it on out-of-sample data, providing a more realistic view of future performance|
| Performance Metrics |	Sharpe Ratio, Sortino Ratio, Maximum Drawdown |	Sharpe Ratio, Calmar Ratio, Risk Parity Ratio |	MVO prioritizes metrics like Sharpe Ratio, while HRP focuses on risk parity measures like Calmar Ratio |
| Suitability for Investor Types |	Short-term traders, risk-seeking investors	| Long-term investors, risk-averse investors	| MVO is better for those seeking active portfolio management, while HRP is better for those seeking passive, long-term stability |


