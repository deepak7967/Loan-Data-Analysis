# Loan Data Analysis & Financial Risk Dashboard (Power BI)

## Project Overview
This project involves building an interactive Default Loan Data Analysis and Financial Risk Dashboard using Power BI with a strong focus on data modeling , DAX calculations , and financial risk analysis  to understand
customer behavior , financial demographics,loan performance, and credit risk . It provides insights that can help financial institutions make better lending and risk management dcisions .
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
   - Power BI
   - Power Query Editor - Data cleaning & transformation
   - DAX(Data Analysis Expressions) - Measures & Calculations
   - Excel - CSV Data and for validation
## Dashboard Pages & Insights
#### Page 1 : Loan Data Overview
![Page1](https://github.com/deepak7967/Loan-Data-Analysis/blob/main/Page1.png)
- Insights
   * Unemployed and part - time applicants show higher default risk , indicating employment type as a key risk indicator .
   * Home loans contribute the highest the total loan amount , indicating strong demand for long - term secured loans .
   * Middle-aged peoples have highest avg income , reflecting stable income and higher financial commitments .
   * Full-time employees earn the highest avg income , making them financially stable and and also have lowest default rate making them least risky borrower segment .
#### Page 2 : Applicant Financial Demographic and Profile
![Page2](https://github.com/deepak7967/Loan-Data-Analysis/blob/main/Page2.png)
- Insights
   * Married applicants generally take higher average loans compared to single applicants , especially in middle-age groups .
   * Borrowers with very low and low credit scores account for a large share of total loan amount .
   * Adults and middle-aged applicants dominate the loan distribution .
   * Applicants with a Bachelor's degree have the highest number of loans , suggesting higher credit participation at this education level .
#### Page 3 : Financial Risk Metrics
![Page 3](https://github.com/deepak7967/Loan-Data-Analysis/blob/main/Page3.png)
 - Insights
   * Borrowers with high DTI ratios record the highest number of defaults , confirming DTI as a critical risk metric .
   * High-income and full-time employed applicants contribute the largest share of total loan amount indicating higher loan capacity .
   * Combining DTI ratio,credit score,and employment type helps clearly identify high-risk borrower segments .
## Future Enhancements 
 - Add predictive model for default risk 
 - Add intrective slicers & drill-through pages
 - Include machine learning-based risk scoring
### Author
Deepak kumar
Aspiring Data Analyst
