# Multi-Feature Bitcoin Price Forecasting Pipeline

## 📌 Project Overview
An end-to-end Machine Learning data pipeline built entirely in a resource-constrained mobile development environment. The project ingests real-time financial data, handles multivariate feature engineering, trains a regression model, and evaluates performance against test data splits.

## 🛠️ Architecture & Tech Stack
- **Environment:** Google Colab Cloud Infrastructure
- **Data Ingestion:** Yahoo Finance API (`yfinance`)
- **Feature Engineering:** 7-Day Simple Moving Average (SMA), 14-Day Relative Strength Index (RSI) via Pandas
- **Predictive Modeling:** Scikit-Learn Multivariate Linear Regression
- **Performance Measurement:** R² Score Evaluation
- **Visual Analytics:** Matplotlib

## 📈 Key Results & Metrics
- **Model Evaluation:** Achieved a predictive performance baseline **R² Score of 0.9966** on unseen testing datasets, demonstrating robust pattern-matching capability when evaluating technical indicator trends alongside closing asset values.
