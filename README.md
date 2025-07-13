# Sharpe Ratio Optimization with Bayesian Search

This repository explores how to optimize a simple Double Moving Average Crossover (DMAC) trading strategy using Bayesian Optimization, with the Sharpe Ratio as the objective function.

It includes:
- Historical data from multiple tickers using `yfinance`
- An Optuna-based parameter search to maximize risk-adjusted return
- A comparison of DMAC vs. Buy & Hold performance on unseen test data
- Visualizations of cumulative returns and trade signals
- Results across assets like Ford, Tesla, Verizon, and MP Materials

The project focuses on building a structured and repeatable experiment for strategy evaluation, rather than chasing the best possible returns.
