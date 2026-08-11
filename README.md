# 📈 Apple Stock Market Analysis — EDA

## 📌 Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of historical **Apple Inc. (AAPL)** stock market data.

The analysis focuses on Apple's historical stock prices, trading volume, daily returns, extreme price movements, and the relationship between trading activity and price movements.

The project uses **Python, NumPy, Pandas, and Matplotlib** to transform historical stock-market data into clear and meaningful insights.

> **Note:** This project is focused on historical exploratory analysis and is not intended to provide investment advice or predict future stock prices.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze Apple's long-term closing-price trend.
* Identify the highest and lowest historical closing prices.
* Analyze trading volume over time.
* Understand Apple's daily return pattern.
* Identify the largest daily gains and losses.
* Examine the relationship between trading volume and price movements.
* Generate business-oriented insights from historical stock data.

---

## 📂 Dataset

The dataset used in this project is the **Huge Stock Market Dataset** available on Kaggle.

For this analysis, only the **Apple (AAPL)** stock data was selected.

### Dataset Information

| Attribute         | Details                   |
| ----------------- | ------------------------- |
| Dataset           | Huge Stock Market Dataset |
| Stock             | Apple Inc. (AAPL)         |
| Records           | 8,364                     |
| Original Columns  | 7                         |
| Analysis Period   | 1984–2017                 |
| Missing Values    | None                      |
| Duplicate Records | None                      |

### Original Columns

* `Date`
* `Open`
* `High`
* `Low`
* `Close`
* `Volume`
* `OpenInt`

The `OpenInt` column contained only zero values and was removed because it provided no meaningful variation for the analysis.

---

## 🛠️ Tools & Technologies

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook / Kaggle Notebook**

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

1. Checked the dataset shape and structure.
2. Checked for missing values.
3. Checked for duplicate records.
4. Converted the `Date` column into datetime format.
5. Removed the `OpenInt` column because it contained only zero values.
6. Created a `Daily_Return` column to measure daily percentage price changes.
7. Created an `Absolute_Return` column to analyze the magnitude of daily price movements.

The dataset contained **no missing values and no duplicate records** before analysis.

---

# ❓ Business Questions

The analysis answers six business questions:

### Q1. How has Apple's closing price changed over time?

Apple's closing price increased from **$0.42388** in September 1984 to **$174.67** in November 2017.

This represents an overall increase of approximately **41,107.42%** across the dataset period.

### Q2. What are Apple's highest and lowest closing prices?

* **Highest closing price:** $175.61

* **Date:** November 8, 2017

* **Lowest closing price:** $0.23051

* **Date:** August 15, 1985

### Q3. How has trading volume changed over time?

* **Average daily trading volume:** approximately 106.64 million shares
* **Highest trading volume:** approximately 2.07 billion shares
* **Date:** September 29, 2000

Several other unusually high-volume days occurred during different periods, demonstrating significant variation in trading activity.

### Q4. What is Apple's daily return pattern?

* **Average daily return:** 0.1131%
* **Positive-return days:** 4,141
* **Negative-return days:** 3,915
* **Zero-return days:** 307

Positive-return days were slightly more frequent than negative-return days.

### Q5. What were Apple's largest daily gains and losses?

* **Largest daily gain:** +33.21%

* **Date:** August 6, 1997

* **Largest daily loss:** −51.85%

* **Date:** September 29, 2000

These observations demonstrate that Apple experienced periods of substantial short-term price volatility.

### Q6. Is higher trading volume associated with larger price movements?

The correlation between trading volume and absolute daily return was:

**0.4194**

High-volume days, defined as days with approximately **225.76 million shares or more**, had:

* **Average absolute return:** 3.6262%

Other days had:

* **Average absolute return:** 1.7569%

This indicates a moderate positive relationship between trading activity and the magnitude of daily price movements.

> Correlation indicates association, not causation.

---

# 📊 Key Insights

The major findings from the analysis are:

* Apple's historical closing price experienced substantial long-term growth.
* The stock reached a historical dataset maximum closing price of **$175.61** in 2017.
* Trading volume varied considerably across the analyzed period.
* Daily returns were relatively balanced between positive and negative trading sessions.
* The largest daily gain was **33.21%**, while the largest daily loss was **−51.85%**.
* High-volume trading days experienced considerably larger average price movements.
* Trading volume and absolute daily return showed a **0.4194 correlation**.

---

# 💡 Business Recommendations

Based on the exploratory analysis:

* Monitor unusually high trading volume because it can coincide with larger price movements.
* Track daily returns to identify periods of unusual volatility.
* Consider long-term price trends alongside short-term movements.
* Investigate extreme gain and loss days to understand the market conditions surrounding them.
* Use multiple indicators such as price, volume, and returns rather than relying on a single metric.

> These observations are based on historical data and should not be interpreted as investment advice.

---

# 🏁 Conclusion

This project analyzed **8,364 historical AAPL trading records** covering the period from 1984 to 2017.

The analysis explored long-term price trends, price extremes, trading volume, daily returns, extreme market movements, and the relationship between trading activity and price volatility.

The findings demonstrate how **Python, NumPy, Pandas, and Matplotlib** can be used to transform historical financial data into meaningful analytical insights.

The project also provides a practical example of applying Exploratory Data Analysis techniques to a real-world financial dataset.

---

## 📚 References

* **Kaggle — Huge Stock Market Dataset**
  https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

* **Pandas Documentation**
  https://pandas.pydata.org/docs/

* **NumPy Documentation**
  https://numpy.org/doc/

* **Matplotlib Documentation**
  https://matplotlib.org/stable/

---

## 👤 Author

**L Shubham**

Data Analyst | Python | SQL | Power BI | Excel | Tableau

---

⭐ If you found this project useful, consider giving the repository a star.
