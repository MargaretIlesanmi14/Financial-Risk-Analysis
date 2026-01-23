# Financial Risk Analysis

## Project Overview
This project analyzes loan application data to uncover borrower behavior, financial risk indicators, and potential default trends. The analysis combines data cleaning and preprocessing in Python with exploratory data analysis and visualization in Power BI to support data-driven lending decisions.

---

## Dataset
- **Source:** Kaggle – Financial Risk Analysis Dataset  
- **Records:** 20,000 loan applications  
- **Features:** 23 variables covering borrower demographics, financial metrics, loan characteristics, and risk indicators  

---

## Tools & Technologies
- **Python (Google Colab):** Data cleaning, preprocessing, feature engineering  
- **Power BI:** Exploratory Data Analysis (EDA) and dashboard creation  

---

## Data Preparation
The dataset was cleaned and preprocessed in Google Colab before being imported into Power BI. Key preparation steps included:
- Handling missing and inconsistent values
- Correcting data types (dates, percentages)
- Normalizing financial ratios (DTI, Credit Utilization, Interest Rate)
- Creating grouped variables for:
  - Age
  - Credit Score
  - Years in Employment

---

## Exploratory Data Analysis (EDA)
Key exploratory insights include:
- Loan applications are highly concentrated in the **600–699 credit score range**
- The majority of borrowers have **0–4 years of employment**, indicating higher exposure to job market volatility
- Debt-to-Income (DTI) ratios show an upward trend over time
- Payment delays are increasing, serving as an early warning signal of financial stress
- The total collateral value exceeds total loan exposure by approximately $469 million, providing strong portfolio protection

---

## Key Findings
- Rising Debt-to-Income ratios indicate borrowers are becoming increasingly financially overextended
- Despite strong collateral coverage, borrower repayment capacity is weakening
- Mid-credit score borrowers and early-career employees represent the highest exposure segments
- Self-employed borrowers exhibit higher risk due to income volatility

## High Risk Flag
A borrower is High Risk if ANY of the following is true:
- Credit Score is less than 600, OR
- Debt-to-Income Ratio is greater than 40%, OR
- Payment Delays in the last 6 months are more than 2

---

## Risk Assessment & Forward-Looking Insights

### What is likely to happen next?
Persistently high DTI levels between 2018 and 2023 suggest borrowers will have reduced disposable income, increasing the likelihood of payment delays and potential defaults.

### Which customers are most likely to default?
The highest-risk borrower segments include:
- Credit score range 600–699
- Employees with 0–4 years of work experience
- Self-employed borrowers with high DTI ratios  

These groups are most vulnerable to cash-flow-related repayment issues.

### What will loan patterns likely look like next month?
- Continued dominance of borrowers aged 30–59
- Increased preference for longer loan tenors (60–84 months) to reduce monthly payment burden
- Ongoing concentration in mid-range credit score segments
- Higher collateral requirements to offset rising borrower risk

---

## Recommendations
- Introduce stricter DTI ceilings for new applicants to mitigate over-leverage
- Attract 800+ credit score borrowers through promotional interest rates
- Reassess pricing strategies for self-employed borrowers, who currently receive lower average interest rates despite higher risk
- Implement enhanced monitoring for borrowers with 0–4 years of employment, the largest exposure group

---

## Project Outputs
- Cleaned dataset (`.csv`)
- Python notebook for data cleaning and preprocessing (`.ipynb`)
- Power BI dashboard (`.pbix`)

---

## Author
Margaret Ilesanmi
