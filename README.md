# MSFT vs NVDA Stock Investment Analysis – ACC102 Data Product

## 1. Product Information

- Module Code: ACC102
- Student Name: [Your Name]
- Student ID: [Your ID]
- Track: Track 2 – GitHub Data Analysis Project
- Product Title: **Risk-Return Analysis of Microsoft (MSFT) and NVIDIA (NVDA) Stocks for Investment Decision Support**
***
## 2. Analytical Purpose & Target Audience
This data product compares the risk and return performance of Microsoft (MSFT) and NVIDIA (NVDA). It helps users evaluate which stock better fits their investment preferences by computing key financial indicators and visualizing results.
### Intended Users:
  Individual US stock investors

  Finance students and researchers

  Personal investment advisors

  Anyone needing data-driven comparisons of tech stock performance
***
## 3. Dataset Description
- Source: Yahoo Finance (yfinance API)
- Content: Daily adjusted closing prices (2020–01–01 to 2025–01–01)
- Instruments: MSFT, NVDA, S&P 500 (^GSPC)
  
### Reason for selection:
Reliable and widely used financial data
Sufficient length and frequency for stable indicator calculation
Covers bull and volatile market periods
Aligns with business/finance context required by ACC102
***
## 4. Python Workflow
- Data Acquisition: Download prices using yfinance
- Data Cleaning: Remove missing values and ensure date alignment
- Transformation: Compute daily returns
### Analysis:
**Annualized return & volatility**

**Maximum drawdown**

**Sharpe ratio**

**Beta coefficient (market sensitivity)**

**Correlation matrix**

**Visualization: Cumulative returns, bar charts, heatmap**

**Output: Final dataset exported to CSV**

***
## 5. Key Outputs & Insights
- Comprehensive metrics table
- Comparative charts for all indicators
- High positive correlation between MSFT and NVDA
  
  NVDA: higher return, higher risk, higher Beta

  MSFT: more stable, lower volatility and drawdown
- Final cleaned dataset for further analysis
***
## 6. Libraries Used
plaintext

yfinance, pandas, numpy, matplotlib, seaborn
***
## 7. How to Run
1. Install dependencies: `pip install yfinance pandas numpy matplotlib seaborn`
2. Open `MSFT_NVDA_Analysis.ipynb in Jupyter`
3. Run cells sequentially
4. View charts, metrics, and exported CSV
***
## 8. Ethical & Compliance Notes
- Data used for educational purpose only
- Source clearly acknowledged
- No sensitive or proprietary data included
- This is for analysis only, NOT investment advice
***
## 9. AI Disclosure (Required by ACC102)
Tools used: Gemini,Doubao

Date: [2026/4/25]

Purpose: Code debugging, explanation, reflection report drafting, and language polishing
