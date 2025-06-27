# 📊 Smart Algo-Trader

> ⚡ An AI-powered automated stock trading system using Python, SQL, ML, APIs, and real-time alerts.

---

## 🚀 Overview

**Smart Algo-Trader** is a modular, intelligent stock trading pipeline that:
- 📈 Fetches real-time stock data (AAPL, MSFT, GOOGL)
- 🤖 Predicts next-day trends using Machine Learning (Decision Trees)
- 📊 Detects technical signals using RSI + Moving Averages
- 📤 Logs trades to Google Sheets
- 🔔 Sends BUY/SELL alerts via Telegram
- 🧠 Includes an Agent AI decision module (optional)
- 📊 Visualizes trades in a dashboard

---

## 🧠 Features

| Module | Description |
|--------|-------------|
| `01_data_fetcher_US.ipynb` | Fetches stock data using Alpha Vantage API |
| `02_strategy_logic.ipynb` | Detects RSI + MA crossover for trade signals |
| `03_backtester.ipynb` | Compares strategy vs market performance |
| `04_ml_predictor.ipynb` | Predicts direction using Decision Tree Classifier |
| `05_google_sheets_logger.ipynb` | Logs trades to Google Sheets |
| `06_telegram_alerts.ipynb` | Sends real-time Telegram alerts |
| `07_automated_runner.ipynb` | Automates daily pipeline execution |
| `08_readme_generator.ipynb` | Auto-generates README summary |
| `dashboard.ipynb` | Interactive strategy dashboard with signal plots |

---

## 🖥️ Tech Stack

- Python 3.10+
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (ML)
- yfinance or Alpha Vantage (data APIs)
- gspread + Google Sheets API
- Telegram Bot API
- SQLite (optional)
- Streamlit (optional dashboard UI)

---

## 📦 Folder Structure

