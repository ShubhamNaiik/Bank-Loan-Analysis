# Bank-Loan-Analysis
## Overview

This Power BI project analyzes historical loan application data from a financial institution. It explores borrower behavior, loan performance, and key indicators to support strategic decision-making in credit risk management and product development.


## Objective

- Understand monthly loan trends and application volumes
- Identify patterns in borrower demographics and loan purpose
- Detect risk through interest rates, DTI, and loan status
- Optimize lending strategies based on regional and behavioural insights

##  Dashboard Views

<p align="center">
  View the full Power BI report <a href="https://app.powerbi.com/groups/me/reports/92e5a99a-9b1a-48c3-81cf-8d21a191d44e/ac198d86a3098ccb235a?experience=power-bi">HERE</a>

![image](https://github.com/user-attachments/assets/bf265ddf-c99d-4bca-8099-17960debebc4)

![image](https://github.com/user-attachments/assets/5149e603-5e42-403b-a0ea-be44c76e7ef1)

![image](https://github.com/user-attachments/assets/70e309ed-2801-49f3-8940-65a8ff995f09)



## Dataset Description


| Variable               | Description                                                 |
|------------------------|-------------------------------------------------------------|
| id                     | Unique customer loan identifier                             |
| address_state          | State of residence of the customer                          |
| application_type       | Type of application (Individual/Joint)                      |
| emp_length             | Length of employment (e.g., 10+ years, <1 year)             |
| emp_title              | Job title of the applicant                                  |
| annual_inc             | Annual income of the applicant                              |
| loan_amount            | Loan amount requested                                       |
| int_rate               | Interest rate of the loan                                   |
| term                   | Term of the loan (36/60 months)                             |
| grade                  | Grade assigned to the loan (A to G)                         |
| sub_grade              | Sub-grade within loan grade (e.g., A1, B3)                  |
| loan_status            | Loan status (e.g., Fully Paid, Charged Off)                 |
| purpose                | Purpose of the loan (e.g., credit card, debt consolidation) |
| dti                    | Debt-to-Income ratio                                        |
| home_ownership         | Home ownership status (e.g., RENT, OWN)                     |
| issue_date             | Issue date of the loan                                      |



## Key Insights

### 1. Loan Application Growth
- **Total Applications**: 38.6K  
- **MoM Growth**: +6.9%  
- **Highest Month**: December (4.3K applications)  
 Consistent increase throughout the year highlights rising demand and possibly seasonal loan behavior.
                           ![image](https://github.com/user-attachments/assets/78747ee0-8aba-4bb4-a082-b0a73aef335b)

     ![image](https://github.com/user-attachments/assets/f983770b-4911-4fed-9308-245a105c9848)


### 2.  Loan Purpose Distribution
- **Top Purpose**: Debt Consolidation (18K)
- Followed by Credit Card Loans (5K) and Home Improvement (3K)  
 Majority of applicants seek financial restructuring, making this a key focus area for product development.

![image](https://github.com/user-attachments/assets/2bda055d-b82e-457c-9443-fc9fbcd96629)


### 3.  Home Ownership & Borrowing
- **Renters**: 18K  
- **Mortgage Holders**: 17K  
Renters dominate the applicant pool; tailored credit strategies may be required to manage risk.

![image](https://github.com/user-attachments/assets/bbab61e5-6df6-43a3-aebe-c67b6d5cf0a7)

### 4. Employment Length Trends
- **10+ Years**: 8.9K applications (most common)  
Longer employment correlates with higher creditworthiness and application volume.

![image](https://github.com/user-attachments/assets/221fd074-6597-498e-8c07-96a94c3143f6)

### 5. Loan Grades & Status
- **Good Loans**: 86.2%  
- **Bad Loans (Charged Off)**: 13.8%  
- **Most Funded Grades**: B & C  
High funding in mid-grade loans with good repayment history. Risk increases in Grades D and below.

![image](https://github.com/user-attachments/assets/85dd603d-9a31-4631-90d5-046693c8519b)

### 6.  Interest Rate & DTI Analysis
- **Avg Interest Rate**: 12.0%  
- **Avg DTI**: 13.3%  
- **Charged-Off Loans**:
  - Interest Rate: 13.88%
  - DTI: 14.00%  
 High-interest loans with DTI > 13% show elevated default rates. Threshold-based monitoring is recommended.

![image](https://github.com/user-attachments/assets/aa9991e4-d9e9-43d7-b454-456b049bbbc2)


## Recommendations

1. **Create Specialized Debt Consolidation Products**  
   Tailor offerings for the most popular loan purpose to enhance conversions and reduce risk.

2. **Build Credit Models for Renters**  
   Since renters form the largest group, use alternative data to assess creditworthiness.

3. **Focus on Stable Employment Segments**  
   Personalize promotions and approvals for applicants with >10 years of work history.

4. **Monitor High-Risk Segments by Grade and DTI**  
   Implement stricter approvals for loans with Grade D or DTI over 13%.

5. **Use State-Level Trends for Marketing Allocation**  
   Prioritize high-performing states or regions in promotional strategies.
