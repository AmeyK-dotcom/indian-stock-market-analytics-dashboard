# 📊 Indian Stock Market Analytics Dashboard

An end-to-end data analytics project built using **MySQL + Tableau** to analyze Indian stock market trends, generate trading signals, and evaluate risk vs return.

---

## 🚀 Project Overview

This project simulates a real-world financial analytics system by combining:

- SQL-based data processing
- Feature engineering (returns, volatility, signals)
- Interactive Tableau dashboard

It analyzes **14 NIFTY stocks** over multiple months to provide actionable insights.

---

## 🧠 Key Features

### 📈 Price & Moving Average Analysis
- 7-day and 30-day moving averages
- Trend identification using crossover logic

### 🤖 Trading Signals
- BUY / SELL / HOLD classification
- Signal strength based on MA difference

### 📊 Volatility & Risk Analysis
- Standard deviation of returns
- Stock risk ranking

### 🔥 Performance Heatmap
- Daily return visualization across all stocks

### 📉 Returns Trend
- Multi-stock daily return fluctuations

### 🎯 Risk vs Return Analysis
- Scatter plot for portfolio insights
- Identifies high-return / low-risk stocks

### 🧩 Signal Distribution
- Market sentiment overview

---

## 🛠 Tech Stack

- **MySQL** → Data cleaning & feature engineering  
- **Tableau** → Dashboard & visualization  
- **Excel / CSV** → Data handling  

---

## 🗂 Data Pipeline

1. Raw stock CSVs imported into MySQL  
2. Created `stock_master` using window functions:
   - Moving averages
   - Previous close (LAG)
   - Daily returns  
3. Built `stock_volatility` for risk metrics  
4. Combined into `stock_final` dataset  
5. Exported final dataset to Tableau  

---

## 📊 Dashboard Preview

<img width="1749" height="1061" alt="Dashboard 1" src="https://github.com/user-attachments/assets/6d7206de-11ed-4214-9a8e-f66759f74ca4" />


---

## 📁 Project Structure

├── sql/
│ └── stock_dashboard_pipeline.sql
├── docs/
│ └── dashboard_notes.md
├── screenshots/
│ └── dashboard.png
└── README.md


---

## 🔍 Key Learnings

- Handling real-world data issues (row limits, nulls, inconsistencies)
- Using SQL window functions for financial calculations
- Designing dashboards for storytelling, not just visuals
- Combining multiple analytical perspectives (trend, risk, signals)

---

## 💡 Future Improvements

- Add RSI / MACD indicators  
- Real-time data integration  
- Portfolio optimization model  

---

## 🙌 Author

Built as a portfolio project to demonstrate skills in:
**SQL | Tableau | Data Analytics | Financial Analysis**
