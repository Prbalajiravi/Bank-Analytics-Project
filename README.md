# Bank-Analytics-Project

## About
This project focuses on analyzing bank loan data to gain insights into loan performance, applicant behavior, and recovery trends. The aim is to identify high-performing and underperforming loans, understand loan status patterns, and analyze recovery metrics. The dataset includes information on loan applications, funded amounts, repayment status, and recovery processes.

## Pupose Of Project
The primary goal of this project is to analyze bank loan data to understand factors influencing loan performance and recovery. The analysis will help identify opportunities for improving loan approval processes, enhancing recovery strategies

## About the data
The analysis involves multiple datasets related to bank loans. Here’s a summary of the datasets and their columns

## Finace 1 Table Meta data
This dataset contains information about loans, including details on loan amounts, borrower information, and loan statuses. Below is a description of each column in the dataset.
### Columns Description
**id** : A unique identifier for each loan record.

**member_id** :  Unique identifier for the borrower.

**loan_amnt** : The total amount of the loan requested by the borrower.

**funded_amnt** : The total amount of the loan that has been funded by the bank.

**funded_amnt_inv** : Shows how much of the requested loan amount has been covered by investors. If the funded amount is less than the requested amount, the remaining amount may be provided by other investors or from the bank's profit.

**term** : The duration of the loan, typically expressed in months.

**int_rate** : The annual interest rate on the loan.

**installment** : The amount the borrower pays per month.

**grade** : A rating assigned to the loan based on the borrower’s creditworthiness. Grades range from A to G.

Grade A: Indicates the lowest risk and highest credit quality. Borrowers usually have excellent credit scores and financial stability.

Grade B: Slightly higher risk than Grade A but still considered good credit quality.

Grade C: Represents moderate risk and credit quality. Borrowers may have some credit issues or lower credit scores.

Grade D: Higher risk with more credit issues. Borrowers may have lower credit scores and less financial stability.

Grade E: High risk with significant credit issues.

Grade F: Very high risk. Borrowers have poor credit histories and may be less likely to repay.

Grade G: The highest risk category. Borrowers have very poor credit histories and are least likely to repay.

**subgrade** : Sub-grades offer a finer level of detail to assess the loan’s risk and quality. They help investors and lenders make more precise decisions.

**loan_status** : The current status of the loan.
Current: Indicates that the borrower is making payments according to the agreed schedule. The loan is performing as expected.
Paid Off: Indicates that the loan is completed, and no further payments are required. This status marks the successful conclusion of the loan agreement.
Charged Off: Indicates that the borrower is unable to pay or has not paid the loan for a long period, resulting in a financial loss.

**dti** : The Debt-to-Income Ratio (DTI), showing the percentage of the borrower’s income that goes towards debt payments, including loans, credit card bills, and other EMIs.

## Finance 2 table Meta data
This table contains detailed information about the borrowers and their payment behaviors. Below is a description of each column in the dataset.

### Columns Description

**id** : Unique identifier for each loan record.

**delinq_2yrs** : Number of times the borrower has been delinquent on loan payments in the last 2 years.

**earliest_cr_line** : The date when the borrower’s first credit account was opened.

**inq_last_6mths** : Number of inquiries made by banks about the borrower's credit in the last 6 months.

**mths_since_last_delinq** : Number of months since the borrower last missed a payment.

**mths_since_last_record** : Number of months since the last public derogatory record (e.g., bankruptcy) was recorded.

**open_acc** : Number of current credit lines open for the borrower (e.g., credit cards, loans).

**pub_rec** : Number of public records indicating financial problems (e.g., bankruptcies) for the borrower.

**revol_bal** : Amount spent using credit cards that is not included in the total payments.

**revol_util** : Percentage of the total credit limit that the borrower is currently using.

**total_acc** : Total number of credit accounts opened by the borrower, including closed accounts.

**out_prncp** : Amount still owed by the borrower.

**out_prncp_inv** : Balance amount from the borrower still due to investors.

**total_pymnt_inv** : Total payments made to investors by the borrower, which may include principal and interest.

**total_rec_prncp** : Total principal amount received by the borrower from the bank.

**total_rec_int** : Total interest amount received by the borrower on the principal loan amount.

**total_rec_late_fee** : Total amount of late fees paid by the borrower due to missed payments.

**recoveries** : Amount of money collected from the borrower after default, often through collection agencies.

**collection_recovery_fee** : Additional fees charged to the borrower for late payments, including collection agency fees.

**last_pymnt_d** : Date of the borrower’s last payment.

**last_pymnt_amnt** : Amount paid by the borrower in their last transaction.

**next_pymnt_d** : Date of the borrower’s next scheduled payment.

**last_credit_pull_d** : Date when the borrower’s credit was last checked.

## Analysis List

**Summary**

Overview of loan performance by status (Good, Bad).
Summary of loan amounts, funded amounts, and recovery amounts.
Distribution of applicants by home ownership type.

**Applicant Insights**

Breakdown of applicants by loan purpose, state, and employment length.
Monthly loan application trends.
Analysis of applicants by home ownership.

**Performance Metrics**

Analysis of revolving balances by grade and sub-grade.
Year-wise funded amounts.
Comparison of verified vs. non-verified loans.
Principal loan amount due by home ownership type.

**Recovery Analysis**

Year-wise analysis of home ownership vs. last payment date.
Enquiry status in the last 6 months.
Recovery amounts by home ownership type.
Collection agency fees by grade charged to the loan.

## Approach Used

**Data Wrangling**: Inspect data for NULL values and missing data, replace or impute missing values, and ensure data consistency across tables.

**Exploratory Data Analysis (EDA)**: Perform exploratory analysis to address key business questions and identify trends, patterns, and anomalies.

## Technology Used

**Power BI**: For creating interactive dashboards and visualizations.

**Power Query Editor**: For data cleaning and transformation.

**Power Pivot**: For managing data models and complex calculations.

## Business Questions To Answer

### Summary
How many unique loan statuses are there?
What are the total and average funded amounts by loan status?
How does home ownership type affect loan performance?
What is the distribution of loan statuses by state?

### Applicant Insights
What are the most common loan purposes?
How do loan applications vary by state and employment length?
What are the monthly trends in loan applications?
How does home ownership type impact loan application trends?

### Performance Metrics
What are the revolving balances by loan grade and sub-grade?
How do funded amounts vary by year?
What is the impact of loan verification on performance?
What is the principal amount due by home ownership type?

### Recovery Analysis
What are the recovery trends year-wise by home ownership type?
What is the enquiry status trend over the last 6 months?
How does the recovery amount vary by home ownership type?
What are the collection agency fees by loan grade?

## Conclusion
The Bank Analytics Project provides a detailed view of loan performance, applicant behavior, and recovery trends. Using Power BI for visualization, Power Query Editor for data transformation, Power Pivot for data modeling, and SQL for validation, the analysis offers actionable insights into loan management and recovery strategies. Key findings highlight trends in loan performance, recovery effectiveness, and applicant characteristics, informing strategies to optimize loan portfolios and improve recovery processes.



