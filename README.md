# Portfolio-Optimisation-Mini-Project
The Portfolio Optimisation Mini Project is a comprehensive Python-based analysis focusing on maximizing the Sharpe Ratio through brute-force and gradient descent methodologies, complete with yfinance API data handling and a risk management decorator for financial transactions.

## Overview

This project focuses on portfolio optimization, specifically aiming to maximize the Sharpe Ratio through various methods, including brute force and gradient descent. It is structured into three main sections: portfolio optimization, control of yfinance API requesting, and implementation of a risk management decorator for financial transactions.

### Table of Contents
- [Portfolio Optimization](#portfolio-optimization)
  - [Using Brute Force Method](#using-brute-force-method)
  - [Using Gradient Descent To Get Optimal Weight For A Specific Sharpe Ratio](#using-gradient-descent-to-get-optimal-weight-for-a-specific-sharpe-ratio)
- [Control yfinance API Requesting](#control-yfinance-api-requesting)
- [Implementing a Risk Management Decorator for Financial Transactions](#implementing-a-risk-management-decorator-for-financial-transactions)

## Portfolio Optimization
The portfolio optimization section is divided into two methodologies:
1. **Using Brute Force Method:** This method involves iterating over numerous potential asset weight combinations to find the one that yields the highest Sharpe Ratio, based on historical return data.
2. **Using Gradient Descent:** An approach to find the optimal asset allocation for a given Sharpe Ratio by minimizing a loss function through gradient descent.

## Control yfinance API Requesting
This section covers the practical aspect of fetching historical price data for assets in your portfolio using the yfinance API. It emphasizes efficient data handling and API usage to retrieve necessary financial data.

## Implementing a Risk Management Decorator for Financial Transactions
The project includes the implementation of a decorator in Python to manage risk in financial transactions. This decorator is a design pattern aimed at adding risk management features to existing functions or methods without modifying their structure.

## Getting Started
To run this project, ensure you have Python installed on your machine along with the following libraries:
- `yfinance` for fetching financial data
- `numpy` and `pandas` for data manipulation
- `matplotlib` for data visualization



