# Bank-Loan-Analysis
## Introduction  
This Power BI report uses interactive dashboards to provide a comprehensive analysis of bank loan applications. The objective is to identify trends, key metrics, and potential risks associated with loan applications to support data-driven decision-making for financial institutions.

## Objective  
The primary objective of this dashboard is to analyze historical bank loan application data to uncover patterns, trends, and insights that help evaluate loan performance, identify customer behaviour, and support decision-making in lending strategies.

## Dataset Description  

| Column Name        | Data Type | Description                                                                 |
|--------------------|-----------|-----------------------------------------------------------------------------|
| id                 | int64     | Unique identifier for each loan application                                |
| address_state      | object    | State from which the application was submitted                             |
| application_type   | object    | Type of loan application (e.g., individual, joint)                         |
| emp_length         | object    | Length of the applicant’s employment                                       |
| emp_title          | object    | Job title of the applicant                                                 |

This data was visualized to extract actionable insights for strategic financial planning.

## Core Questions  
This analysis focuses on addressing the following questions:
1. What is the overall trend of loan applications month over month?
2. Which states have the highest and lowest number of loan applications?
3. What are the most common purposes of loan applications?
4. How does employment length impact the number of loan applications?
5. What is the average interest rate and debt-to-income (DTI) ratio?
6. How do home ownership status and loan grades relate to loan approvals?  

## Key Insights  
- Total Loan Applications: 38.6K with 6.9% MoM growth 
- Highest applications were recorded in December (4.3K)
- Majority of applications were for Debt Consolidation (18K), followed by Credit Card loans (5K)  
- Renters submitted more applications (18K) than mortgage holders (17K)  
- Applicants with 10+ years of employment had the highest applications (8.9K)  
- Average Interest Rate:** 12%  
- Average DTI: 13.3%  

## Recommendations  
1. Focus on **marketing loan consolidation programs** as they dominate demand
2. Improve **credit risk assessment** among renters
3. Offer **personalized loan terms** to individuals with longer employment histories
4. Monitor loan grades for better **fund allocation and approval tracking**  

## Conclusion  
This dashboard highlights critical insights into loan application behaviour and performance. It empowers financial teams to make data-driven decisions, optimize loan products, and streamline approval processes. 
