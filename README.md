An interactive financial analytics dashboard built using Python, Streamlit, Pandas, NumPy, SciPy, and Yahoo Finance API.
The dashboard computes portfolio performance, risk metrics, and loss probability estimates used in quantitative finance and risk management roles.

This project showcases strong skills in data analytics, risk modeling, financial mathematics, and building production-ready dashboards — key for analyst roles at Goldman Sachs.

🚀 Key Features
📈 1. Portfolio Performance Metrics

Annualized Returns

Annualized Volatility

Sharpe Ratio (risk-adjusted return)

⚠️ 2. Risk Management Tools

Historical Value at Risk (VaR)

Historical Conditional VaR (CVaR)

Supports multi-asset portfolio calculations

📉 3. Real-Time Stock Data Fetching

Uses Yahoo Finance (yFinance) API

Supports multiple tickers (AAPL, MSFT, GOOG, etc.)

🖥️ 4. Fully Interactive Streamlit Dashboard

Enter any stock ticker(s)

Select date range

Automatic computation of all metrics

View price data & log returns instantly

🧮 5. Modular Code Architecture

/src contains risk & return calculation logic

/dashboard/app.py for UI

Easy to extend to CAPM, Monte Carlo, efficient frontier, etc.

📁 Project Structure
financial-risk-analytics-dashboard/
│── README.md
│── requirements.txt
│── src/
│   ├── portfolio_metrics.py
│   └── var_cvar.py
│── dashboard/
│   └── app.py
│── data/           # optional: store CSVs here

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/financial-risk-analytics-dashboard.git
cd financial-risk-analytics-dashboard

2️⃣ Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt
How It Works
✔ Step 1 — Fetch Stock Prices

Using Yahoo Finance API, the dashboard fetches daily adjusted close data.

✔ Step 2 — Compute Log Returns

Cleaner and more mathematically sound for financial analysis.

✔ Step 3 — Calculate Portfolio Metrics

Uses:

Mean returns

Covariance matrix

Risk-free rate (user-configurable)

✔ Step 4 — Evaluate Downside Risk

Using historical simulation method:

VaR (95%)

CVaR (95%)

✔ Step 5 — Display Results

Metrics, tables, and insights appear instantly.

📚 Technologies Used

Python 3.10+

Streamlit (interactive dashboard UI)

Pandas / NumPy (data analysis)

SciPy (statistics & calculations)

Matplotlib (plots)

yFinance API (market data)

🎯 Use Cases

This project is ideal for:

Quantitative finance learning

Investment research

Portfolio analytics presentations

Interview preparation for Goldman Sachs risk/analyst roles

Showcasing financial modeling skills on GitHub

🌟 Future Enhancements (Optional)

Efficient Frontier & Mean-Variance Optimization

Monte Carlo VaR Simulation

Beta & CAPM Analysis

Sharpe Ratio Optimization Tool

Market Regime Detection
