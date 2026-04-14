# Portfolio Optimization Script
## Overview
This repository contains a Python script for optimizing a portfolio using the concept of Marginal Contribution to Risk (MCR). The script downloads historical price data for a list of tickers, calculates the daily returns, and then optimizes the portfolio to minimize the sum of squared differences of the MCRs.

## Features
* Downloads historical price data for a list of specified tickers using Yahoo Finance.
* Calculates daily returns for the specified tickers.
* Computes the covariance matrix of returns.
* Optimizes the portfolio to equalize the Marginal Contribution to Risk (MCR) across all assets.
## Files
```portfolio_optimization.py```: Python script containing the functions and logic for downloading data, calculating returns, and optimizing the portfolio.
