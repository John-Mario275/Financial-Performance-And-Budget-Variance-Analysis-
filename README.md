# Financial-Performance-And-Budget-Variance-Analysis
An interactive financial analysis project developed to evaluate budget performance across departments and accounts using Power BI.
## Business Problem Statement
Management currently faces difficulties identifying the departments and accounts responsible for significant deviations from budgeted financial expectations due to inconsistencies in reported figures. A reliable actual-versus-budget analysis is needed to establish a clear basis for measuring financial performance, distinguishing favourable from unfavourable variances and prioritising material issues for further investigation.
## Company Background
Meridian Community Services Network is a simulated organisation used as the foundation for this financial analysis. The project examines its departmental financial performance through budget monitoring, variance assessment and performance reporting to provide management with reliable insights for planning, accountability and strategic decision-making.
## Objectives of the Analysis
The analysis aims to:
- Identify departments and accounts with the highest absolute and percentage budget variances.
-	Assess the extent to which revenue shortfalls and expenditure overruns influence overall financial performance.
-	Evaluate monthly and year-to-date movements in budget variances.
-	Highlight material variances requiring investigation and accountability from departmental owners.
-	Establish the evidence required to determine whether identified variances result from timing differences, non-recurring events or persistent financial pressures.
## Dataset Description
The project uses a financial dataset containing 638 original records covering January 2025 to June 2026.
The dataset contains six columns:
-	Period
-	Department
-	Account
-	Type
-	Budget
-	Actual
  
It covers five departments: Administration, Customer Service, Operations, Sales and Technology.

Currency: Nigerian Naira (₦).

## Tools and Technologies Used
-	Microsoft Power BI
-	Power Query
-	DAX
-	CSV dataset

## Methodology
The analysis followed a systematic process involving the following stages:

- **Data Profiling and Assessment**: Examined the dataset to identify missing values, duplicate records, inconsistencies and other data quality issues.
- **Data Cleaning and Transformation**: Used Power Query to clean, restructure and prepare the financial records for analysis.
- **Financial Measure Development**: Created calculated measures using DAX to support financial performance evaluation.
- **Variance Calculation**: Computed actual values, budget figures, absolute variances and percentage variances.
- **Performance Analysis**: Evaluated financial performance across departments, accounts, income and expenditure categories.
- **Materiality Assessment**: Applied a 5% materiality threshold to identify significant budget deviations requiring management attention.
- **Trend Analysis**: Examined monthly and year-to-date financial movements to identify performance patterns and emerging trends.
- **Dashboard Development and Reporting**: Designed interactive Power BI dashboards to communicate findings and support management decision-making.
## Exploratory Data Analysis
The exploratory data analysis focused on examining financial performance across the organisation through the following areas:

- **Variance Assessment**: Examined absolute and percentage budget variances across departments and financial accounts.
- **Income and Expenditure Analysis**: Evaluated revenue and expenditure performance against their respective budget allocations.
- **Trend Analysis**: Investigated monthly and year-to-date financial movements to identify performance patterns and fluctuations.
- **Materiality Assessment**: Identified significant variances exceeding the 5% materiality threshold and distinguished them from below-threshold deviations.
- **Performance Classification**: Assessed favourable and unfavourable financial outcomes based on the nature of income and expenditure variances.
## Key Findings
The analysis revealed the following key findings:

**OVERALL FINANCIAL PERFORMANCE**
- Combined actual and budget totals amounted to approximately ₦24.05 million, comprising ₦12.11 million in actuals and ₦11.93 million in budget allocations.
- The organisation recorded an absolute variance of approximately ₦175.55 thousand, representing an overall variance of 1.47%, below the established 5% materiality threshold.

**DEPARTMENTAL AND ACCOUNT-LEVEL PERFORMANCE**
- Technology recorded the highest departmental absolute variance at approximately ₦79,000.
- Payroll recorded the largest account-level absolute variance at approximately ₦72,000.

**INCOME AND EXPENDITURE PERFORMANCE**
- Expenditure actuals of approximately ₦10.322 million exceeded the budget of ₦10.187 million, resulting in an unfavourable variance.
- Income actuals of approximately ₦1.788 million surpassed the budget of ₦1.748 million, indicating favourable revenue performance.

**MONTHLY PERFORMANCE TRENDS**
- February 2025 recorded the highest expenditure absolute variance at approximately ₦68,000.
- June 2025 recorded the highest income absolute variance at approximately ₦22,000.
- May 2026 recorded the highest income absolute variance at approximately ₦29,000.
- June 2026 recorded the highest expenditure absolute variance at approximately ₦27,000.
  
**MATERIALITY ASSESSMENT**
- Certain accounts across the departments recorded material variances exceeding the 5% threshold, with Customer Service exhibiting the most unfavourable financial performance.
