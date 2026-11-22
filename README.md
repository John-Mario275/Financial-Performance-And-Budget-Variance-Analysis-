# Financial-Performance-And-Budget-Variance-Analysis
An interactive financial analysis project developed to evaluate budget performance across departments and accounts using Power BI.

## Table of Contents

- [Project Title](#financial-performance-and-budget-variance-analysis)
- [Business Problem Statement](#-business-problem-statement)
- [Company Background](#-company-background)
- [Objectives of the Analysis](#-objectives-of-the-analysis)
- [Dataset Description](#-dataset-description)
- [Tools and Technologies Used](#-tools-and-technologies-used)
- [Methodology](#-methodology)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Key Findings](#-key-findings)
- [Visualizations](#-visualizations)
- [Dashboard Screenshots](#-dashboard-screenshots)
- [Business Insights](#-business-insights)
- [Recommendations](#-recommendations)
- [Limitations](#-limitations)
- [Future Improvements](#-future-improvements)
- [Repository Structure](#-repository-structure)
- [Contributors](#-contributors)
- [References](#-references)


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

## **Visualizations**

The Power BI dashboards incorporated the following visuals to address the project objectives:

- **KPI Cards:** Display key financial indicators, including YTD totals, actuals, budget, absolute variance, variance percentage, threshold, materiality status and financial performance.
- **Absolute Variance by Department:** Highlights departments with the largest financial deviations.
- **Absolute Variance by Account:** Identifies accounts contributing most to budget variances.
- **Income and Expenditure Performance:** Compares actual revenue and expenditure against their respective budgets.
- **Monthly Variance Trends:** Tracks changes in financial variances across the reporting period.
- **Detailed Variance Table:** Highlights material department-account combinations and their financial performance status.

## **Dashboard Screenshots**

The Power BI report consists of three interactive dashboard views:

1. **Overall Financial Performance:** Provides a summary of the organisation's financial position.
2. **Expenditure Performance:** Examines spending patterns and budget variances.
3. **Income Performance:** Evaluates revenue performance against budget expectations.
## Dashboard Screenshots

![Overall Performance](Dashboard%20Screenshots/overall-performance.png)

### Expenditure Performance
![Expenditure Performance](Dashboard%20Screenshots/expenditure-performance.png)

### Income Performance
![Income Performance](Dashboard%20Screenshots/income-performance.png)
## **Business Insights**

The analysis revealed the following key insights:
- Technology recorded the highest departmental absolute variance, while Payroll had the largest account-level variance.
- Expenditure overruns were the primary contributor to the unfavourable expenditure position, despite income exceeding budget expectations.
- Although the overall variance of 1.47% remained below the 5% materiality threshold, specific department-account combinations recorded material variances.
- The trend analysis reveals inconsistent financial performance across the reporting periods, with monthly variances fluctuating considerably from the organisation’s budget targets.
- Material variances highlighted specific accounts requiring further management attention and departmental accountability.
- While the dataset identifies the magnitude and location of financial deviations, it does not contain sufficient supporting records to establish their underlying causes.

## **Recommendations**

Based on the findings of the analysis, the following recommendations are proposed:

**Departmental and Account-Level Review:** Management should prioritise departments and specific accounts with the largest material variances for review to ensure that significant deviations receive appropriate attention.

**Variance Accountability:** The organisation is encouraged to request explanations from relevant department owners for significant differences between actual and budgeted figures and ensure that appropriate corrective actions are implemented.

**Income and Expenditure Control:** Management should strengthen expenditure monitoring to address budget overruns while sustaining activities that contribute to income performance in line with budget expectations.

**Monthly and YTD Monitoring:** The organisation should establish regular monthly and YTD budget reviews to monitor fluctuations in financial performance, identify inconsistent patterns across reporting periods and address deviations from budget targets early.

**Supporting Documentation:** Management should ensure that accurate invoices, payment records and departmental reports are maintained to support further investigation into whether identified variances result from timing differences, one-off events or recurring financial pressures.

## **Limitations**

The analysis was subject to the following limitations:

**Limited Supporting Records:** Invoice-level records, payment records and detailed departmental financial schedules were not available to support a more comprehensive investigation of the variances.

**Unverified Variance Causes:** The underlying causes of individual variances could not be independently established, making it difficult to determine whether they resulted from timing differences, one-off events or recurring financial pressures.

**Missing Budget Values:** Eight budget values were missing from the supplied dataset and were therefore excluded from variance percentage calculations to avoid misleading results.

**Scope of Available Data:** The analysis was limited to the financial data supplied, which restricted the extent of additional investigation and validation that could be carried out.

## **Future Improvements**

To enhance the accuracy, efficiency and overall value of the financial analysis, the following improvements are recommended:

**Integration of Supporting Records:** The organisation should integrate invoice-level records, payment records and detailed departmental schedules to enable more thorough investigation and verification of financial variances.

**Budget Validation and Control:** Management should incorporate approved budget revisions and Finance control totals to improve data accuracy, ensure consistency and strengthen the reliability of financial reporting.

**Automated Financial Reporting:** The organisation is encouraged to automate monthly and YTD financial reporting to reduce manual processes, improve reporting efficiency and provide management with timely financial information.

**Financial Forecasting:** Management should introduce financial forecasting to anticipate future income and expenditure patterns, support budget planning and enable proactive financial decisions.

**Continuous Variance Monitoring:** The organisation should strengthen recurring variance monitoring and investigation to identify unusual financial patterns, understand their underlying causes and take timely corrective actions.

## Repository Structure

The project repository is organised into folders to make the dataset, Power BI dashboard, visual outputs and supporting documentation easy to locate and access.

```text
Financial-Performance-Budget-Variance/
│
├── Dataset/
│   └── dataset_raw.csv
│
├── Dashboard/
│   └── Financial_Performance_Dashboard.pbix
│
├── Screenshots/
│   ├── Overall_Performance.png
│   ├── Expenditure_Performance.png
│   └── Income_Performance.png
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

**Folder descriptions:**
- **Dataset:** Contains the raw financial dataset used for the analysis.
- **Dashboard:** Contains the Power BI dashboard file.
- **Screenshots:** Contains images of the three dashboard views: overall, expenditure and income performance.
- **Documentation:** Contains the detailed project report in PDF format.
- **README.md:** Provides an overview of the project, including its objectives, methodology, key findings, recommendations and limitations.

##** Contributors**

- **Project Analyst:** John Idajor
- **Mentor:** Mr. Mfon

## **References**

The following resources were consulted and used in carrying out this project:

1. Project 03: *Financial Performance & Budget Variance Analysis* (Mentorship Project).
2. Supplied financial dataset (`dataset_raw.csv`).
3. Microsoft Power BI Documentation: [https://learn.microsoft.com/en-us/power-bi/](https://learn.microsoft.com/en-us/power-bi/)
4. Microsoft DAX Documentation: [https://learn.microsoft.com/en-us/dax/](https://learn.microsoft.com/en-us/dax/)
