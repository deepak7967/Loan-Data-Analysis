# Loan Data Analysis & Financial Risk Dashboard (Power BI)

## Project Overview
This project analyzes 255,347 loan records to help financial institutions identify default risk patterns and understand borrower behavior. Data was stored and managed on Azure SQL Server, cleaned using Power Query, and visualized through a two-page Power BI dashboard covering overall loan performance and applicant demographic profiling. Custom DAX measures were built to track Year-over-Year loan trends, default rates, and segment-level loan distributions. and financial risk analysis  to understand
customer behavior , financial demographics,loan performance, and credit risk . It provides insights that can help financial institutions make better lending and risk management dcisions .
## Business Problem
Financial institutions face a critical challenge: approving loans to the right applicants while minimizing default risk. Without visibility into borrower behavior across income levels, employment types, credit categories, and age groups, lenders are exposed to significant financial loss.
## Objectives 
- Analyze loan distribution across different purpose , age groups , and credit categories
- Identify high-risk customers using financial risk metrics
- Study default patterns over time
- Understand the impact of income , employment type,education , and DTI ratio on loan defaults
- Understand Year on Year change in Loan amount and Default rate 
## Dataset Description
The dataset used in this project contains loan details and performance collected across multiple years . 
- original Columns
    * Applicant Demographics - Age , Marital Status , Education Level , Employement Type
    * Financial Information - Income , DTI Ratio
    * Loan Details - Loan Id , Loan Amount , Loan Date , Purpose
    * Credit & Risk Indicators - Credit Score , Default Status
- Created Columns
    * Category Columns - Age Group , Income Category , DTI Category , Credit Category
    * Date - Year
 - Calculated Measures
    * Default Rate , year on year (YOY) Loan Amount Change , YOY Default rate change , Avg Loan Taken By Adults
## Tools & Technologies Used
   - Azure
   - MSSQL
   - Power BI
   - Power Query Editor - Data cleaning & transformation
   - DAX(Data Analysis Expressions) - Measures & Calculations
   - Excel - CSV Data and for validation
## Dashboard Pages & Insights
#### Page 1 : Loan Data Overview
![1st_page](https://github.com/deepak7967/Loan-Data-Analysis/blob/main/1st_page.png)
- Insights
   * YOY Loan Amount Change — Peaked in 2015 (+1.3%), declined in 2014 (−1.5%) and 2017 (−1.1%), recovered strongly to +1.3% in 2018 .
   *  Unemployed and part - time applicants show higher default risk , indicating employment type as a key risk indicator .
   * Home loans contribute the highest the total loan amount , indicating strong demand for long - term secured loans .
   * Middle-aged peoples have highest avg income , reflecting stable income and higher financial commitments .
   * Full-time employees earn the highest avg income , making them financially stable and and also have lowest default rate making them least risky borrower segment .
   * YOY Loan Amount Change — Peaked in 2015 (+1.3%), declined in 2014 (−1.5%) and 2017 (−1.1%), recovered strongly to +1.3% in 2018 .

#### Page 2 : Applicant Financial Demographic and Profile
- Insights
   * Married applicants generally take higher average loans compared to single applicants , especially in middle-age groups .
   * Borrowers with very low and low credit scores account for a large share of total loan amount .
   * Adults and middle-aged applicants dominate the loan distribution .
   * Applicants with a Bachelor's degree have the highest number of loans , suggesting higher credit participation at this education level .
## Future Enhancements 
 - Add predictive model for default risk 
 - Add intrective slicers & drill-through pages
 - Include machine learning-based risk scoring
#### Author
Deepak kumar<br>
Aspiring Data Analyst
