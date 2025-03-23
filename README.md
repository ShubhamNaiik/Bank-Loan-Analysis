# Bank-Loan-Analysis
## Overview

This Power BI project analyzes historical loan application data from a financial institution. It explores borrower behavior, loan performance, and key indicators to support strategic decision-making in credit risk management and product development.

---

## Objective

- Understand monthly loan trends and application volumes
- Identify patterns in borrower demographics and loan purpose
- Detect risk through interest rates, DTI, and loan status
- Optimize lending strategies based on regional and behavioural insights

---
## 📸 Dashboard Views

> View the full Power BI report [🔗 here](#) 
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

---

## 🔍 Key Insights

### 1. 📈 Loan Application Growth
- **Total Applications**: 38.6K  
- **MoM Growth**: +6.9%  
- **Highest Month**: December (4.3K applications)  
> 📌 Consistent increase throughout the year highlights rising demand and possibly seasonal loan behavior.

---

### 2. 🧾 Loan Purpose Distribution
- **Top Purpose**: Debt Consolidation (18K)
- Followed by Credit Card Loans (5K) and Home Improvement (3K)  
> 📌 Majority of applicants seek financial restructuring, making this a key focus area for product development.

---

### 3. 🏠 Home Ownership & Borrowing
- **Renters**: 18K  
- **Mortgage Holders**: 17K  
> 📌 Renters dominate the applicant pool; tailored credit strategies may be required to manage risk.

---

### 4. 👩‍💼 Employment Length Trends
- **10+ Years**: 8.9K applications (most common)  
> 📌 Longer employment correlates with higher creditworthiness and application volume.

---

### 5. 🏷️ Loan Grades & Status
- **Good Loans**: 86.2%  
- **Bad Loans (Charged Off)**: 13.8%  
- **Most Funded Grades**: B & C  
> 📌 High funding in mid-grade loans with good repayment history. Risk increases in Grades D and below.

---

### 6. 📊 Interest Rate & DTI Analysis
- **Avg Interest Rate**: 12.0%  
- **Avg DTI**: 13.3%  
- **Charged-Off Loans**:
  - Interest Rate: 13.88%
  - DTI: 14.00%  
> 📌 High-interest loans with DTI > 13% show elevated default rates. Threshold-based monitoring is recommended.

---

## ✅ Recommendations

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
