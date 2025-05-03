# Dynamic-Tail-Risk

This repository contains the code and analysis for a financial risk modeling project focused on dynamic tail risk estimation using a range of Extreme Value Theory (EVT) techniques, under Dr. Elliot Noma's guidance.

## 📈 Project Overview

The project evaluates the effectiveness of various tail risk estimation methods applied to the XLF ETF (Financial Select Sector SPDR Fund) from 2010 to 2024, including:

- **Static models:** Empirical VaR, Normal VaR, Student-t VaR
- **Extreme Value Theory (EVT) models:** 
  - Static Generalized Pareto Distribution (GPD)
  - Monte Carlo GPD simulation
  - Rolling GPD on returns and drawdowns
  - **Autoregressive Extreme Value (AEV)** model

Backtesting is conducted using the **Kupiec Proportion of Failures (POF)** test, and performance is evaluated through violation rates and exceedance tracking.

## 🔍 Key Features

- VaR and Expected Shortfall estimation at 99% confidence
- Rolling window backtesting for model calibration
- Tail fraction and threshold tuning for EVT models
- Drawdown-based and return-based risk metrics
- Visualizations of rolling risk levels and exceedance clustering
