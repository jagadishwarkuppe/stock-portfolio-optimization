# stock-portfolio-optimization

# 📈 Stock Portfolio Optimization Using Modern Portfolio Theory

## Overview
This project implements a quantitative portfolio optimization framework using Modern Portfolio Theory (MPT). 
The objective is to construct an optimal portfolio allocation that maximizes risk-adjusted return using 
Monte Carlo simulation and Sharpe ratio optimization.

## Key Features
- Historical stock data collection using Yahoo Finance API
- Daily return calculation and preprocessing
- Annualized return and volatility computation
- Covariance and correlation matrix analysis
- Monte Carlo simulation (10,000 portfolios)
- Sharpe ratio maximization
- Efficient Frontier visualization
- Value at Risk (VaR) calculation
- Maximum Drawdown analysis

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- yfinance

## Methodology
1. Download historical price data
2. Compute daily returns
3. Estimate annual return and volatility
4. Construct covariance matrix
5. Generate random portfolio weights
6. Compute portfolio return, risk, and Sharpe ratio
7. Select portfolio with maximum Sharpe ratio
8. Evaluate downside risk using VaR and Maximum Drawdown

## Results
The optimized portfolio demonstrates:
- Strong risk-adjusted performance (Sharpe Ratio > 1)
- Diversified allocation across multiple sectors
- Controlled downside risk using VaR metrics

## Project Outcome
This project demonstrates strong understanding of:
- Quantitative finance principles
- Risk modeling
- Statistical simulation
- Financial data visualization
- Portfolio risk management
