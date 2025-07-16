# 📊 Predictive Impact of Merger Announcements on Bidder Company Performance

This repository contains a data science project that transforms an MSc Finance dissertation into a predictive analytics workflow. It analyzes the **short-term and long-term effects of merger announcements** on **bidder companies’ stock performance, shareholder returns, trading volumes, volatility, and synergies**.

---

## 🧠 Project Overview

This project aims to answer the question:

> **Do merger announcements significantly impact the stock performance and market value of the acquiring (bidder) companies?**

Using real-world M&A data from the U.S. banking sector (2000–2019), the project explores how stock returns, market cap, and trading volumes change before and after merger announcements. It also quantifies the effect of synergies (net interest income and personnel expenses) on post-merger performance.

---

## 🎯 Objectives

- 📈 Analyze stock performance, volatility, and market capitalization pre- and post-merger
- 📊 Measure the relationship between trading volume and stock returns using correlation and R²
- 💼 Evaluate synergies by tracking financial statement variables
- 🔮 Build a predictive framework for assessing future merger impact

---

## 🏦 Companies Studied

| Ticker | Bidder Company           | Merger Year | Target Acquired     |
|--------|---------------------------|-------------|----------------------|
| BAC    | Bank of America           | 2007        | LaSalle Bank         |
| JPM    | JPMorgan Chase            | 2004        | Bank One             |
| MTB    | M&T Bank                  | 2011        | Wilmington Trust     |
| PNC    | PNC Financial Services    | 2005        | Riggs Bank           |
| TFC    | Truist (formerly BB&T)    | 2019        | SunTrust Bank        |

---

## 🧪 Methodology

This project follows a **deductive, quantitative event study** approach.

### 📋 Data Sources
- [Yahoo Finance](https://finance.yahoo.com)
- [S&P Global](https://www.spglobal.com)
- Company press releases and financial reports

### 📐 Statistical Methods
- Average Returns & Standard Deviation
- Variance & Volatility
- Correlation between Volume and Price
- R-squared Regression Analysis

### 🧰 Tools & Libraries
- Python (pandas, numpy, seaborn, matplotlib, statsmodels)
- Jupyter Notebooks
- Excel (for validation)
- Streamlit (optional dashboard)

---

## 📈 Key Results (from Dissertation Findings)

- **Shareholder returns declined** after most mergers in the short term
- **Volatility increased** for JPM, PNC, and Truist after mergers
- **Trading volume had weak predictive power** (R² < 36%)
- **Synergies** boosted net interest income but increased personnel costs
- **Market Cap** increased for JPM, PNC, and Truist, but declined for BAC and M&T

---

## 📦 Repository Structure
