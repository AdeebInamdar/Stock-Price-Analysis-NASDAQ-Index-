## 📈 Stock Price Data Analysis

This repository contains a data analysis project focused on stock market data for four major technology companies: **Apple (AAPL)**, **Microsoft (MSFT)**, **Netflix (NFLX)**, and **Alphabet/Google (GOOG)**.

The analysis is performed using Python with the **Pandas** library for data manipulation and **Matplotlib** for static visualization.

---

## 🎯 Analysis Objectives

The primary goal of this analysis is to provide a comparative study of the four stocks across several key financial indicators over the given time period:

1.  **Price Trend:** Track the daily price movement to identify overall performance and market trends.
2.  **Price Volatility:** Analyze the distribution of closing prices to compare stock stability.
3.  **Liquidity:** Evaluate the total trading volume to gauge market interest and liquidity.
4.  **Risk & Return:** Examine the distribution of daily percentage returns to assess risk (volatility) and average daily performance.

---

## 📊 Visualizations

The analysis generates four distinct plots:

### 1. Closing Price Over Time (Line Plot)
* **Insight:** Shows the historical price evolution and relative gains/losses over the time frame.
* **Key Finding:** Identifies the highest-priced stocks (MSFT, GOOG) and overall market direction.

### 2. Closing Price Distribution (Box Plot)
* **Insight:** Compares the median, range, and interquartile range of closing prices for volatility assessment.
* **Key Finding:** **NFLX** generally shows the tightest price distribution, suggesting lower dollar-value volatility, while **MSFT** and **GOOG** have a larger spread.

### 3. Total Trading Volume (Bar Chart)
* **Insight:** Quantifies total market activity for each stock.
* **Key Finding:** **AAPL** dominates in total shares traded, indicating the highest liquidity among the group.

### 4. Distribution of Daily Percentage Returns (Histograms)
* **Insight:** Visualizes the frequency of daily gains and losses, which is critical for assessing risk (standard deviation of returns).
* **Key Finding:** **AAPL** has the tightest distribution (lower volatility/risk), while **NFLX** shows the widest spread, including the most extreme single-day returns (highest volatility/risk).

---

## 🛠️ Requirements and Setup

To run this analysis locally, you will need:

1.  **Python 3.x**
2.  The `pandas` and `matplotlib` libraries.
3.  The `stocks.csv` dataset in the project root directory.

You can install the necessary Python packages using pip:

```bash
pip install pandas matplotlib
