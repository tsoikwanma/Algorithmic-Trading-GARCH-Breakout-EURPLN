# EUR/PLN GARCH Volatility Breakout Strategy

This academic project develops a volatility-based breakout trading strategy using EUR/PLN tick-level bid and ask data. The strategy uses GARCH(1,1) volatility forecasts to create dynamic trading bands and generate buy/sell signals.

## Strategy

The final strategy is based on:

* GARCH(1,1) volatility forecasting
* volatility breakout bands
* EMA-smoothed price signal
* transaction cost adjustment
* out-of-sample performance testing

## Performance

Out-of-sample results:

* Gross P&L: 384 PLN
* Net P&L: 350 PLN
* Gross Sharpe Ratio: 0.69
* Net Sharpe Ratio: 0.64
* Number of transactions: 2

## Files

* `project-476914.ipynb` — full notebook with data processing, modelling, backtesting, and results.
* `eurpln.csv` — tick-level data.

## Libraires

Python, Pandas, NumPy, Matplotlib, Statsmodels, arch, Jupyter Notebook.
