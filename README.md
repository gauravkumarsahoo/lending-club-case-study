# Lending Club Case Study
> This project involves analyzing loan data to gain insights into patterns and trends that can help in making data-driven decisions. The dataset includes various attributes related to loans, such as loan amounts, interest rates, funded amounts, annual incomes, and borrower information.

The primary goals of this project are:

1. Data Cleaning and Preprocessing:
    * Identify and address missing values, duplicate records, and irrelevant columns.
    * Standardize data formats by removing unnecessary suffixes and ensuring uniformity across numerical fields.

2. Exploratory Data Analysis (EDA):
    * Understand the relationships between key financial variables, such as loan amounts, interest rates, and debt-to-income ratios.
    * Visualize distributions and correlations using tools like correlation matrices and plots.

3. Insights and Recommendations:
    * Derive actionable insights from the analysis to improve loan processing, risk assessment, and portfolio management.

This project emphasizes clear and structured data handling, enabling more accurate analysis and decision-making in the financial domain. 

## Table of Contents
* Loading and Understanding Data
* Data Cleaning and Manipulation
* Univariate Analysis
* Bivariate Analysis/Multivariate Analysis

## General Information
This project focuses on analyzing loan data to uncover meaningful insights that can aid in financial decision-making and risk assessment.
- Background: The project is based on a real-world dataset containing information about loans, borrowers, and repayments. The data is rich with details such as loan amounts, interest rates, borrower incomes, and more.
- Business Problem: The analysis aims to address challenges in loan management, such as identifying factors affecting defaults, optimizing loan approvals, and improving investor confidence by providing transparent insights into the loan portfolio.
- Dataset: The dataset includes various attributes, such as loan_amount, funded_amount, interest_rate, installments, annual_income, and debt_to_income. It also contains borrower-specific details and other metadata, some of which were cleaned or removed during preprocessing.

## Conclusions
- Univariate Analysis
    - Loan Amount: Most loans range between 5,500 to 15,000, with outliers above 30,000.
    - Funded Amount: Similar to loan amounts, funded amounts mostly fall between 5,400 to 15,000, with outliers above 30,000.
    - Interest Rate: Primarily between 9.25% and 14.59%, with outliers above 22.5%.
    - Debt-to-Income Ratio: Generally between 8.17% and 18.6%.
    - Loan Term: Loans with a 3-year term are almost three times more common than 5-year loans.
    - Borrower Grades: Most loans are taken by borrowers with Grade B, A, and C, particularly in sub-grades B3, A4, A5, B5, B4, and C1.
    - Defaults: About one-sixth of loans are charged off, indicating a significant rate of defaults.
    - Homeownership: Many loans are taken by individuals who rent or mortgage their homes.
    - Loan Purpose: Debt consolidation is the most common reason for borrowing.
    - Income Verification: A majority of loans are granted to individuals with unverified income sources.
    - Loan Issuance Growth: The number of loans issued has increased year over year, reflecting growing demand.
    - Monthly Trends: Loan issuance shows a steady increase throughout the year, particularly from January to December.

- Bivariate/Multivariate Analysis:
    - Loan Amount vs Loan Status: Higher loan grades are associated with smaller loan amounts.
    - Funded Amount vs Loan Status: Lower-grade borrowers tend to receive larger funded amounts, increasing default risk.
    - Interest Rate vs Loan Status: Higher interest rates in lower grades are linked to higher defaults.
    - Installment vs Loan Status: Higher installments in lower grades increase the likelihood of defaults.
    - Annual Income vs Loan Status: Borrowers with higher incomes and lower grades (considering G being lowest) are more likely to default.
    - Debt-to-Income Ratio vs Loan Status: High DTI ratios in lower grades indicate over-leveraged borrowers, increasing default risk.

- Correlations:
    - Loan Amount & Funded Amount (0.98): Highly correlated, as the funded amount is directly tied to the loan amount.
    - Loan Amount & Installment (0.93): Larger loan amounts result in higher installment payments.
    - Funded Amount & Installment (0.96): Funded amounts also heavily influence installment size.
    - Funded Amount & Funded Amount by Investors (0.96): These two variables are highly correlated and directly proportional.

- Risk Factors:
    - Lower-Grade Loans: Loans with lower grades (E, F, G) tend to have higher loan amounts, interest rates, and DTI ratios, increasing the likelihood of default.

- Income Influence:
    - Higher Annual Incomes: Borrowers with higher incomes are more likely to fully repay loans.

- Current Loans:
    - Current Loans: These loans often have higher loan amounts, funded amounts, and installments, particularly in lower grades, indicating they are still at risk of default.

- Key Findings:
    - Shorter Terms, Higher Grades, Home Ownership, and Debt Consolidation: Loans with these factors are more likely to be fully paid.

## Technologies Used
- NumPy version: 1.26.4
- Pandas version: 2.2.2
- Matplotlib version: 3.8.4
- Seaborn version: 0.13.2

## Acknowledgements
- This project was inspired by a case study provided by upGrad.

## Contact
Created by [@gauravkumarsahoo] - feel free to contact me!