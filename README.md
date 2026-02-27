# DA-intern-Time-Series-Analysis-task
Data on notebook :
https://colab.research.google.com/drive/1GbOPQiWa3_6skBze6efhdiu_7I7IWgFl?usp=sharing

# 📈 Stock Prices Time Series Analysis

A time series analysis project on S&P 500 stock prices data, focusing on trend detection, seasonal decomposition, and moving averages smoothing.

---

## 📁 Dataset Description

The dataset contains daily stock prices for **505 companies** from the S&P 500 index, covering the period from **January 2014 to December 2017**.

| Column | Type | Description |
|--------|------|-------------|
| `symbol` | string | Stock ticker symbol (e.g. AAPL, GOOGL) |
| `date` | datetime | Trading date |
| `open` | float | Opening price of the stock |
| `high` | float | Highest price during the trading day |
| `low` | float | Lowest price during the trading day |
| `close` | float | Closing price of the stock |
| `volume` | int | Number of shares traded during the day |

---

## 🔍 Analysis Overview

### 1. Raw Time Series Plot
Visualizing the stock's close price and volume over the years to get an initial understanding of the data trend.

### 2. Time Series Decomposition
Using `statsmodels` to decompose the time series into three components:
- **Trend** → The long-term direction of the stock
- **Seasonality** → Repeating patterns over time
- **Residuals** → Random noise that can't be explained

### 3. Moving Averages Smoothing
Applying moving averages to smooth out short-term fluctuations:
- **MA-20** → Short-term (Monthly)
- **MA-50** → Medium-term (Quarterly)
- **MA-200** → Long-term (Yearly)

---

## 🛠️ Libraries Used

- `pandas` — Data manipulation
- `matplotlib` — Data visualization
- `statsmodels` — Time series decomposition

---

## 🚀 How to Run

1. Clone the repository
2. Upload the dataset to your environment
3. Run the notebook on [Google Colab](https://colab.research.google.com/)
