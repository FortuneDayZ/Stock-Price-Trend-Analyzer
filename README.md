# 📈 Stock Trend Analyzer

## 🧭 Overview

**Stock Trend Analyzer** is a Jupyter Notebook-based financial analysis tool that helps users visualize and evaluate the performance of selected stocks over time. Using historical data fetched via `yfinance`, the app provides visual insights into trends, moving averages, and relative performance to assist in stock market decision-making.

---

## ✨ Features

- 🔍 **Stock Search & Download**
  - Fetches historical stock data using the `yfinance` Python library.
  - Users can input ticker symbols and date ranges for custom analysis.

- 📊 **Visual Trend Analysis**
  - Line charts showing stock price history.
  - Comparison of daily closing price trends.
  - Support for multiple tickers on the same chart.

- 📈 **Moving Averages**
  - Plots short-term and long-term moving averages to help assess trend momentum.
  - SMA/EMA can be easily configured.

- 🧮 **Volatility & Volume Insights**
  - Candlestick charts with volume overlays.
  - Optional Bollinger Bands and other technical indicators.

- 📓 **Interactive & Reproducible**
  - Built entirely in a Jupyter Notebook for step-by-step exploration.
  - Each code cell can be executed independently for dynamic analysis.

---

## 🛠️ Technologies Used

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**:
  - `yfinance` — to fetch historical market data
  - `matplotlib` / `plotly` — for visualization
  - `pandas` / `numpy` — for data wrangling

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/FortuneDayZ/Stock-Price-Trend-Analyzer.git
```

### 2. Open Google Colab

Upload and Open in Notebook in the Google Colab Website
---

## 📁 File Structure

```
Stock-Trend-Analyzer/
├── Stock_Trend_Analyzer.ipynb    # Main analysis notebook
└── README.md                     # Project documentation
```

---

## ✅ Usage

1. Enter one or more ticker symbols (e.g., `AAPL`, `GOOGL`).
2. Specify the desired date range.
3. Run the cells to fetch, process, and visualize the stock data.
4. Analyze trends, moving averages, and volume patterns.
5. Customize charts or indicators as needed.

---
