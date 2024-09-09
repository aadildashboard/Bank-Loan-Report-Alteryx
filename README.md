
# Bank Loan Report

## Project Overview
This project aims to analyze key loan-related metrics to assess and monitor the performance of the bank's lending activities. By leveraging Alteryx tools, the project processes, transforms, and visualizes data to provide insights that help make data-driven decisions regarding loan portfolios, repayments, and overall loan performance.

## Tools and Technologies
- **Alteryx**: Used for data processing, cleaning, transformation, and insights generation.
- **SQL**: Integrated for querying loan-related data from the database.
- **Excel/CSV**: Data sources used for loan information.

## Key Insights Generated
1. **Total Loan Applications**: Calculated the number of loan applications received for a specific period. The analysis includes Month-to-Date (MTD) and Month-over-Month (MoM) changes.
2. **Total Funded Amount**: Derived the total amount disbursed as loans and tracked MTD and MoM changes.
3. **Total Amount Received**: Measured the total amount repaid by borrowers, including MTD and MoM changes.
4. **Average Interest Rate**: Calculated the average interest rate on all loans, with monthly variation tracking.
5. **Average Debt-to-Income Ratio (DTI)**: Evaluated borrower financial health through the average DTI ratio.

## Loan Category Analysis
- **Good Loans**: These include loans with statuses of 'Fully Paid' or 'Current'. Metrics include:
  - Good Loan Application Percentage
  - Total Good Loan Applications
  - Total Good Loan Funded Amount
  - Total Good Loan Amount Received
- **Bad Loans**: Loans categorized as 'Charged Off'. Metrics include:
  - Bad Loan Application Percentage
  - Total Bad Loan Applications
  - Total Bad Loan Funded Amount
  - Total Bad Loan Amount Received

## Loan Status Categorization
A detailed breakdown of loan statuses was provided, including:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio

## Insights by Categories
1. **Monthly Trends**: Analyzed how loan applications, funded amounts, and repayments vary over time.
2. **Regional Analysis**: Explored lending activity across different states to assess regional disparities.
3. **Loan Term Analysis**: Analyzed loans across various term lengths (e.g., 36 months, 60 months) to identify trends in loan terms.
4. **Employee Length Analysis**: Insight into how borrowers' employment length influences loan applications and disbursements.
5. **Loan Purpose Breakdown**: Analyzed loan metrics based on various loan purposes (e.g., debt consolidation, credit card refinancing).
6. **Home Ownership Analysis**: Assessed how home ownership status impacts loan applications and disbursements.

## Conclusion
The report highlights the bank's loan portfolio's health, identifies key trends, and provides actionable insights to inform lending strategies. By leveraging Alteryx tools, the project efficiently processes large datasets and presents critical loan-related insights.

## Setup Instructions
1. **Install Alteryx**: Ensure you have access to Alteryx Designer.
2. **Load Data**: Place the loan dataset (Excel/CSV) in the `Data/` folder.
3. **Run Workflows**: Use the Alteryx workflows in the `Workflows/` folder to generate the insights.

---
