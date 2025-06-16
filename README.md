# 📈 Stock Trend Analyzer

## 🧭 Overview

**Stock Trend Analyzer** is a Google Colab Notebook-based financial analysis tool that helps users visualize and evaluate the performance of selected stocks over time. Using historical data fetched via `yfinance`, the app provides visual insights into trends, moving averages, and relative performance to assist in stock market decision-making.

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
  - Built entirely in a Google Colab Notebook for step-by-step exploration.
  - Each code cell can be executed independently for dynamic analysis.

---

## 🖼️ Screenshots
###1. Model Summary
Shows the structure of the LSTM-based model used for predictions.

![Image Alt](https://github.com/FortuneDayZ/Stock-Price-Trend-Analyzer/blob/main/Screenshots/LSTM%20Model%20Architecture.png?raw=true)

###2. Moving Averages Visualization
Displays historical Google stock prices along with 100-day and 250-day moving averages.

![Image Alt](image_url)

###3. Predictions vs Real Data
Illustrates how closely the model's predictions follow actual historical test data.

![Image Alt](image_url)

---

## 🛠️ Technologies Used

- **Language**: Python
- **Environment**: Google Colab
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
```
Upload the notebook and open it in Google Colab
```
### 3. Run All
```
Click "Run All" to re-run the notebook and fetch the latest data.
```
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
