## Moving Average Crossover Backtest (SPY, QQQ, NVDA)

This project implements and evaluates a Moving Average Crossover strategy using daily price data from 2000 to 2025.

## The strategy:

Buy when the fast moving average crosses above the slow moving average.

Sell when the fast MA crosses below the slow MA.

Data is downloaded using yfinance.

## Features

Automatic data download (SPY, QQQ, NVDA)

Signal generation (fast MA vs slow MA)

Equity curve computation

Full performance metrics:

Total return

CAGR

Annualized volatility

Sharpe ratio

Max drawdown

Hit ratio

Comparison vs Buy & Hold

Clean, modular Python code

## Example Results (from notebook)

From the PDF (pages 4–7):
Strategy metrics vs SPY, QQQ, NVDA:

Ticker	Total Return	CAGR	Volatility	Sharpe	Max Drawdown
SPY	653%	8.71%	12.27%	0.72	−33.7%
QQQ	1166%	12.79%	20.86%	0.61	−40.92%
NVDA	6450%	20.41%	44%	0.73	−63.73%

(See pages 4–6 of the PDF for full tables.) 

251126_Backtesting a Moving Ave…

## How to Run
pip install yfinance pandas numpy matplotlib


Open the notebook:

Backtesting a Moving Average Crossover Strategy.ipynb

## Future Work

Add slippage + transaction costs

Optimize MA windows

Add risk management

Build multi-asset portfolio

Implement a small backtesting framework

## Author
**Denisse Pareja**  
Quantitative Research & Data Science  
Miami, FL  
