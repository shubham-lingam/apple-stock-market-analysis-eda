# Apple Stock Market Analysis — EDA

An Exploratory Data Analysis (EDA) project analyzing historical Apple Inc. (AAPL) stock market data.

---

## Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of historical **Apple Inc. (AAPL)** stock market data.

The analysis focuses on:

- Historical stock prices
- Trading volume
- Daily returns
- Extreme price movements
- The relationship between trading activity and price movements

The project uses **Python, NumPy, Pandas, and Matplotlib** to transform historical stock-market data into clear and meaningful insights.

> **Note:** This project is focused on historical exploratory analysis and is not intended to provide investment advice or predict future stock prices.

---

## Project Objectives

The main objectives of this project are to:

- Analyze Apple's long-term closing-price trend
- Identify the highest and lowest historical closing prices
- Analyze trading volume over time
- Understand Apple's daily return pattern
- Identify the largest daily gains and losses
- Examine the relationship between trading volume and price movements
- Generate business-oriented insights from historical stock data

---

## Dataset

The dataset used in this project is the **Huge Stock Market Dataset** available on Kaggle.

For this analysis, only the **Apple Inc. (AAPL)** stock data was selected.

### Dataset Information

| Attribute | Details |
|---|---|
| Dataset | Huge Stock Market Dataset |
| Stock | Apple Inc. (AAPL) |
| Records | 8,364 |
| Original Columns | 7 |
| Analysis Period | 1984–2017 |
| Missing Values | None |
| Duplicate Records | None |

### Original Columns

- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`
- `OpenInt`

The `OpenInt` column contained only zero values and was removed because it provided no meaningful variation for the analysis.

---

## Tools & Technologies

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook / Kaggle Notebook**

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

1. Checked the dataset shape and structure
2. Checked for missing values
3. Checked for duplicate records
4. Converted the `Date` column into datetime format
5. Removed the `OpenInt` column because it contained only zero values
6. Created a `Daily_Return` column to measure daily percentage price changes
7. Created an `Absolute_Return` column to analyze the magnitude of daily price movements

The dataset contained **no missing values and no duplicate records** before analysis.

---

## Business Questions

The analysis answers six key business questions.

### Q1. How Has Apple's Closing Price Changed Over Time?

Apple's closing price increased from **$0.42388** in September 1984 to **$174.67** in November 2017.

This represents an overall increase of approximately **41,107.42%** across the dataset period.

---

### Q2. What Are Apple's Highest and Lowest Closing Prices?

- **Highest Closing Price:** $175.61
- **Date:** November 8, 2017

- **Lowest Closing Price:** $0.23051
- **Date:** August 15, 1985

---

### Q3. How Has Trading Volume Changed Over Time?

- **Average Daily Trading Volume:** Approximately 106.64 million shares
- **Highest Trading Volume:** Approximately 2.07 billion shares
- **Date:** September 29, 2000

Several other unusually high-volume days occurred during different periods, demonstrating significant variation in trading activity.

---

### Q4. What Is Apple's Daily Return Pattern?

- **Average Daily Return:** 0.1131%
- **Positive-Return Days:** 4,141
- **Negative-Return Days:** 3,915
- **Zero-Return Days:** 307

Positive-return days were slightly more frequent than negative-return days.

---

### Q5. What Were Apple's Largest Daily Gains and Losses?

- **Largest Daily Gain:** +33.21%
- **Date:** August 6, 1997

- **Largest Daily Loss:** −51.85%
- **Date:** September 29, 2000

These observations demonstrate that Apple experienced periods of substantial short-term price volatility.

---

### Q6. Is Higher Trading Volume Associated with Larger Price Movements?

The correlation between trading volume and absolute daily return was:

**0.4194**

High-volume days, defined as days with approximately **225.76 million shares or more**, had:

- **Average Absolute Return:** 3.6262%

Other days had:

- **Average Absolute Return:** 1.7569%

This indicates a moderate positive relationship between trading activity and the magnitude of daily price movements.

> Correlation indicates association, not causation.

---

## Key Insights

The major findings from the analysis are:

- Apple's historical closing price experienced substantial long-term growth
- The stock reached a historical dataset maximum closing price of **$175.61** in 2017
- Trading volume varied considerably across the analyzed period
- Daily returns were relatively balanced between positive and negative trading sessions
- The largest daily gain was **33.21%**, while the largest daily loss was **−51.85%**
- High-volume trading days experienced considerably larger average price movements
- Trading volume and absolute daily return showed a **0.4194 correlation**

---

## Business Recommendations

Based on the exploratory analysis:

- Monitor unusually high trading volume because it can coincide with larger price movements
- Track daily returns to identify periods of unusual volatility
- Consider long-term price trends alongside short-term movements
- Investigate extreme gain and loss days to understand the market conditions surrounding them
- Use multiple indicators such as price, volume, and returns rather than relying on a single metric

> These observations are based on historical data and should not be interpreted as investment advice.

---

## Conclusion

This project analyzed **8,364 historical AAPL trading records** covering the period from 1984 to 2017.

The analysis explored:

- Long-term price trends
- Price extremes
- Trading volume
- Daily returns
- Extreme market movements
- The relationship between trading activity and price volatility

The findings demonstrate how **Python, NumPy, Pandas, and Matplotlib** can be used to transform historical financial data into meaningful analytical insights.

The project also provides a practical example of applying Exploratory Data Analysis techniques to a real-world financial dataset.

---

## References

- **Kaggle — Huge Stock Market Dataset**  
  https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

- **Pandas Documentation**  
  https://pandas.pydata.org/docs/

- **NumPy Documentation**  
  https://numpy.org/doc/

- **Matplotlib Documentation**  
  https://matplotlib.org/stable/

---

## Author

**L Shubham**

**Data Analyst | Python | SQL | Power BI | Excel | Tableau**

---

If you found this project useful, consider giving the repository a star.
