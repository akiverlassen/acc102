#  Microsoft (MSFT) vs Adobe (ADBE) Investment Analysis

## 1. Product Information

- Module Code: ACC102
- Student Name: [Jianing.Wu]
- Student ID: [2473360]
- Track: Track 2 – GitHub Data Analysis Project
- Product Title: **Risk-Return Analysis of Microsoft (MSFT) and Adobe (ADBE) Stocks for Investment Decision Support**
***
## 2. Analytical Purpose & Target Audience
This data product compares the risk and return performance of Microsoft (MSFT) and Adobe (ADBE). It helps users evaluate which stock better fits their investment preferences by computing key financial indicators and visualizing results.
### Intended Users:
  Individual US stock investors

  Finance students and researchers

  Personal investment advisors

  Anyone needing data-driven comparisons of tech stock performance
***
## 3. Dataset Description
- Source: WRDS (Compustat + CRSP)
- Time range: 2019 – 2024 (annual financials + daily returns)
- Key data: Balance sheet, income statement, stock returns, market benchmark (S&P 500 via SPY)
  
### Reason for selection:
Reliable and widely used financial data
Sufficient length and frequency for stable indicator calculation
Covers bull and volatile market periods
Aligns with business/finance context required by ACC102
***
## 4. Python Workflow
- Data extraction from WRDS using a single connection
- Data cleaning and preprocessing
- Fundamental financial ratio analysis
- Risk & performance metrics calculation
- Visualization and comparison
- Final dataset export
  
### Metrics included:
**Annualized return & volatility**

**Maximum drawdown**

**Sharpe ratio**

**Beta coefficient (market sensitivity)**

**Correlation matrix**

**Visualization: Cumulative returns, bar charts, heatmap**

**Output: Final dataset exported to CSV**

***
## 5. Key Findings
- MSFT shows stronger and more stable profitability over the period.
- ADBE has higher return potential but also higher volatility.
- Both stocks outperform the market with positive alpha.
- MSFT has better risk-adjusted returns (higher Sharpe ratio).
- MSFT and ADBE are strongly correlated with each other and with the S&P 500.

***
## 6. How to Run
1.Install required packages:  
`pip install pandas numpy matplotlib seaborn wrds` 

2. Open the Jupyter notebook

3. Run cells sequentially from top to bottom

4. Ensure you have a valid WRDS account

***
## 7.Product 
- **GitHub Repository**: [https://github.com/akiverlassen/acc102]
- **Notebook**: `ACC102 .ipynb`
***
## 8.Limitations & Improvements
- Limitations: Reliance on historical data; no macroeconomic variables included.
- Improvements: Add peer comparison, include valuation ratios, build a simple forecasting model.

---

## AI Disclosure
- AI tools：Gemini，Doubao
- AI tools were used to assist with code structuring, debugging.

