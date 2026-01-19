# Portfolio Risk Analysis – VaR & Backtesting (Offline)

## 📌 Overview
This project presents an offline portfolio risk analysis using historical market data.
It focuses on volatility estimation, Value at Risk (VaR), backtesting and basic stress testing.
The objective is to demonstrate fundamental concepts of quantitative finance and risk management using Python.

The project is fully offline to ensure reproducibility and independence from external data sources.

---

## 🔧 Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- SQLite
- Excel (automated reporting)

---

## 📊 Implemented Features
- Portfolio returns computation using weighted assets
- Volatility estimation (daily and rolling)
- Historical Value at Risk (VaR 95% and 99%)
- Rolling VaR backtesting with breach analysis
- Simple stress testing scenarios:
  - Equity shock
  - Worst historical day
  - Volatility spike
- Data storage using a SQLite database
- Automated Excel reporting

---

## 📁 Project Structure
portfolio-risk-var/
│
├── risk_var_offline.ipynb # Main analysis (Jupyter Notebook)
├── prices.csv # Offline market price data
├── outputs/
│ ├── report_risk.xlsx # Excel risk report (generated)
│ ├── risk.db # SQLite database
│ └── figures/ # Charts (histograms, rolling volatility, backtest)


---

## 📈 Data
- The input data is stored in `prices.csv`
- Contains daily prices for:
  - S&P 500
  - Apple (AAPL)
  - Gold (GLD)

The data is loaded locally and processed without any internet connection.

---

## 🗄️ Database
The SQLite database (`risk.db`) contains:
- Daily asset returns (long format)
- Portfolio returns and VaR backtesting results

This allows basic SQL queries such as aggregation and breach analysis.

---

## 📑 Output
Running the notebook automatically generates:
- An Excel report with all results
- A SQLite database with structured data
- Multiple charts for visualization

---

## 🎓 Skills Demonstrated
- Quantitative finance fundamentals
- Risk management concepts
- Monte Carlo and statistical reasoning
- Data analysis and visualization
- SQL data storage
- Automated reporting

---

## ▶️ How to Run
1. Place `prices.csv` in the same folder as the notebook
2. Open `risk_var_offline.ipynb`
3. Run all cells
4. Results are generated in the `outputs/` folder

---

## ⚠️ Notes
- This project is educational and not intended for real trading decisions.
- The VaR approach used is historical and has known limitations.

---

## 📬 Contact
This project was developed for academic and learning purposes.
