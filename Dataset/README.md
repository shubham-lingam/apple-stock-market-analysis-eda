# 📂 Dataset

## 📈 Apple (AAPL) Stock Market Dataset

This project uses the **Apple Inc. (AAPL)** historical stock data from the **Huge Stock Market Dataset** available on Kaggle.

The complete Kaggle dataset contains historical price and volume information for multiple U.S. stocks and ETFs.

For this project, only the **AAPL dataset** was selected for analysis.

---

## 🔗 Dataset Source

**Kaggle — Huge Stock Market Dataset**

https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

---

## 📊 Dataset Used

**Stock:** Apple Inc.
**Ticker:** AAPL
**File:** `aapl.us.txt`

### Dataset Details

| Attribute | Details             |
| --------- | ------------------- |
| Stock     | Apple Inc.          |
| Ticker    | AAPL                |
| Records   | 8,364               |
| Columns   | 7                   |
| Period    | 1984–2017           |
| Format    | CSV-style text file |

### Columns

| Column    | Description                          |
| --------- | ------------------------------------ |
| `Date`    | Trading date                         |
| `Open`    | Opening stock price                  |
| `High`    | Highest price during the trading day |
| `Low`     | Lowest price during the trading day  |
| `Close`   | Closing stock price                  |
| `Volume`  | Number of shares traded              |
| `OpenInt` | Open interest                        |

---

## 🧹 Dataset Preparation

The following preparation was performed during the analysis:

* Converted `Date` into datetime format.
* Checked for missing values.
* Checked for duplicate records.
* Removed the `OpenInt` column because all values were `0`.
* Created a `Daily_Return` feature to measure daily percentage price changes.
* Created an `Absolute_Return` feature to measure the magnitude of daily price movements.

The AAPL dataset contained **no missing values and no duplicate records**.

---

## 📌 Note

The dataset is used strictly for **educational and exploratory data analysis purposes**.

The analysis does not provide investment advice, financial recommendations, or predictions of future stock performance.

---

## 👤 Project

**Apple Stock Market Analysis — Exploratory Data Analysis**

Tools used:

* Python
* NumPy
* Pandas
* Matplotlib
* Kaggle Notebook

