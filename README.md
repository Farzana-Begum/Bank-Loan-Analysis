# 🏦 Bank Loan Analysis (Python)
Comprehensive analysis of bank loan performance and borrower behaviour using Python for data processing 
## Project Overview
The Bank Loan Analysis project provides an end-to-end analysis of bank loan data to understand lending performance, repayment patterns, and borrower risk levels.
Using Python, we perform data cleaning, exploratory data analysis (EDA), and generate visual insights that help financial institutions make data-driven decisions.
## Project Objectives
- Analyze overall and monthly loan funding performance.
- Track repayments and default patterns.
- Evaluate portfolio quality through Good vs. Bad Loan metrics.
- Support business decisions on credit policy and risk management.
## Data used
[DataSet](https://github.com/Farzana-Begum/Bank-Loan-Analysis/blob/main/financial_loan.xlsx)
## Tools & Technologies
- Python (Pandas, NumPy).
- Matplotlib/Seaborn (Data visualization).
- Jupyter Notebook / VS Code (Development environment).
- Excel / CSV (Source data format).
- GitHub
## Data Cleaning & Preparation
- Data Loading – Imported CSV using pandas.
- Handled missing values, removed duplicates, fixed datatypes.
- Created new columns like Total funded amount, Total amount received, Average interest rate.
## Exploratory Data Analysis (EDA)
- Analyze loan amount interest rate, funded amount, and income levels distribution.
- Compare relationships between loan status and variables such as loan amount, interest rate, and DTI ratio.
- Overall Loan Performance
   - Total Funded Amount: $435.76M (Total value of all loans disbursed by the bank)
   - MTD Total Funded Amount: $53.98M (Total loan amount disbursed during the current month)
   - Total Amount Received: $473.07M (Total repayments collected from customers (principal + interest).
   - MTD Total Amount Received: $58.07M( Total repayments collected in the current month.)
   - Average Interest Rate: 12.05% (Indicates the average cost of borrowing for applicants.)
   - Average Debt-to-Income Ratio (DTI): 13.33% (Reflects borrower financial stability and repayment capacity)
- The correlation heatmap highlights the relationship between homeownership status and the total funded amount, showing how loan disbursement varies across different ownership categories.
## Questions and key(KPIS)
- What is the total funded amount and total amount received by the bank?
- What is the monthly trend of funded amount and amount received (MTD)?
- What is the loan approval rate across gender, property area, and credit history?
- Which factors influence loan approval the most — income, loan amount, or credit history?
- What is the default rate among applicants with poor credit history?
## Visualization Insights
### Using Matplotlib and Seaborn:
- Loan approvals by property,employee-length,loan purpose,regional state.
- Distribution of loan amounts
- Count of approved vs. rejected loans
- Relationship between credit history and loan approval rate
- Average income vs. loan approval trend
## Project Insights
- Repayment patterns show strong borrower discipline and stable cash flow.
- Strong overall repayments reflect high borrower credibility.
- Good loan performance significantly outweighs bad loan performance, contributing to a healthy loan book.
- The ratio of good-to-bad loans indicates effective credit risk management and sound lending policies.
## Final Conclusion
The bank’s loan portfolio is financially strong, with high repayment performance and stable borrower profiles. Good loans significantly outweigh bad loans, indicating effective credit risk management. Overall, the portfolio shows healthy repayment trends, strong loan quality, and a positive financial outlook.
