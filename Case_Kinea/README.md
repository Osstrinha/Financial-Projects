# Financial Risk Analysis Project

## Overview
This repository contains analyses related to market risk, fixed income valuation, and credit risk assessment. The project is divided into three main parts: market risk evaluation, bond pricing and duration calculation, and corporate credit risk analysis.

## Project Structure

### Part I: Market Risk
This section focuses on risk assessment for a portfolio of 20 selected stocks.

#### Objectives:
1. **Volatility Calculation**: Compute the 12-month volatility for each stock.
2. **Portfolio Volatility**: Evaluate the volatility of an equally weighted portfolio (5% per stock).
3. **Minimum Volatility Portfolio**: Optimize the allocation to minimize portfolio volatility (0-10% per stock).
4. **Maximum Sharpe Ratio Portfolio**: Find the allocation that maximizes the Sharpe ratio, considering constraints (0-10% per stock).

#### Data Sources:
- Historical stock prices from [Okanebox](https://www.okanebox.com.br/)

---

### Part II: Fixed Income Analysis (NTN-B Bonds)
This section focuses on modeling the cash flow of NTN-B bonds with semiannual interest payments.

#### Objectives:
1. **Cash Flow Modeling**: Calculate periodic interest payments and principal repayment based on projected inflation and real interest rates.
2. **Present Value Calculation**: Discount future cash flows to determine the current bond price (PU).
3. **Macaulay Duration**: Compute the bond’s duration to measure its sensitivity to interest rate changes.

#### References:
- [Tesouro Direto Methodology](https://www.tesourodireto.com.br/data/files/5B/86/BD/D8/36B2D610393A62D6894D49A8/Precificacao%20dos%20titulos%20publicos.pdf)
- [ANBIMA Pricing Guidelines](https://www.anbima.com.br/data/files/A0/02/CC/70/8FEFC8104606BDC8B82BA2A8/Metodologias%20ANBIMA%20de%20Precificacao%20Titulos%20Publicos.pdf)

---

### Part III: Credit Risk Analysis
This section evaluates the financial health of a publicly traded Brazilian company to determine its creditworthiness.

#### Objectives:
1. **Company Selection & Business Analysis**: Choose a company and analyze its core business, financial statements, and market position.
2. **Credit Risk Evaluation**: Assess the company's ability to meet financial obligations.
3. **Loan Simulation**: Estimate a reasonable credit amount based on financial metrics and economic conditions.
4. **Macroeconomic Considerations**: Discuss external factors that may influence credit risk.

---

## Technologies Used
- Python (NumPy, Pandas, Matplotlib, SciPy, yfinance)
- Optimization & Financial Modeling Libraries
- Data Visualization Tools


## Contributions
Feel free to contribute by submitting pull requests or reporting issues.

## Contact
For any questions or discussions, reach out via GitHub Issues or email.


