# credit-market-risk-basel3
Credit &amp; Market Risk Aggregation under Basel III
Overview

This project demonstrates the quantification and aggregation of credit and market risk under Basel III and IFRS 9 standards. It is designed as a portfolio risk analysis, including forward-looking stress testing and scenario analysis.

Features

Credit Risk: Estimation of Expected Credit Loss (ECL) using the Home Credit Dataset.

Market Risk: Calculation of Value at Risk (VaR), Conditional VaR (CVaR/Expected Shortfall), and rolling volatility.

Stress Testing: Application of macro-level stress indicators using the St. Louis Fed Financial Stress Index (STLFSI) and scenario analysis.

Aggregation: Combined analysis of credit and market risks for total portfolio risk.

Data Sources

Home Credit Dataset (Kaggle) – for credit risk modeling.

Yahoo Finance – for market risk (LQD, TLT, S&P/TSX Composite Index).

St. Louis Fed FRED – for financial stress index.

Python Libraries

pandas, numpy

yfinance, pandas_datareader

scikit-learn

matplotlib, seaborn
