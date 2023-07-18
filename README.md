# Bank-Loan-Prediction-ML-Classification-Models
Implemented various classification models for predicting bank loan approvals based on cost of misclassification

Table of Contents: 
1. Problem Background and Motivation
2. Libraries and Custom Functions
3. Data Exploration and Data Prep
4. Understanding the Business Problem
5. Machine Learning Models
6. Model Comparison
7. Model Selection
8. Deployment of Model

## 1. Problem Background and Motivation
<b>I. High Level Outline</b>

_Target Variable: approved_<br>

Here we are dealing with the loan details of a large regional bank in order to predict whether or not we can approve loans of new customers. We are presented with data of 689 loan applications including those loans which were not approved.

<img src = 'https://guardhill.com/wp-content/uploads/2021/03/5cscreditblogchart-copy.png'
     height = "325"
     width = "380"
     align = "right"/>
     
Typically, banks consider the 5 Cs of Credit while assessing any potential borrower:
- Character
- Capacity
- Capital
- Collateral
- Conditions




Here, while we may have been given a limited number of data points to work with, I expect the following things shall need to be looked at while predicting task completion (including existing parameters):
- Debt level
- Existing bank customer or not (recorded conduct and history with the bank) 
- Industry that the applicant belongs to (is employed in/ has own business)
- Number of years of employment
- Prior defaults
- Employed/ Students
- Credit Score
- Income levels
- Collateral/ security available
- Other cashflows
- Secondary applicant/ guarantor
- Guarantor details 
- Guarantor collateral/ security
- Debt to income ratio
- Loan to value ratio

<img src = 'https://www.investopedia.com/thmb/xRigJ1OIF1_AyxtvDydgm_D0ASY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/mortgage-preapproval-4776405_final2-f5fbd4d3d08d4aeeb04cc12fc718ae00.png'
     width = "750"/>




