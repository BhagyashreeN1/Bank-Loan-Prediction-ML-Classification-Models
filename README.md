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

<br>
<br>


<b>II. Brief Background</b>

<br>
1. What is the problem?<br>
This part deals with loan approvals by a regional bank.
We are trying to predict the eligibility of new loan applicants basis data of those applicants whose loans were approved or rejected.
<br>
<br>
2. Why is it important?<br>
Loans are a primary source of income for banks, and banks typically have a largr consumer loan vertical which deals with property loans, mortgage loans, car loans and unsecured personal loans.
There is a certain level of risk/ Risk appetite that each bank has on the basis of which it decideds whether to extend loans or not to their applicants.
This includes a vast list of parameters, some of which have been listed above.
It is of utmost importance for the banks to vet the applicants properly to ensure that the loans are being extended to the right people to ensure that the funds extended are recoverable and probability of default is low.
<br>
<br>
3. Who are the key stakeholders?<br>
In this case, this predictor is beneficial for loan departments of banks, loan agents and loan recovery teams.
<br>

<br>
<br>
<b>III. Data Section</b>

In this case, we have been given information of existing loan applicants along with details of those applicants whose loans have been rejected in the past. Based on this data, we need to predict whether loans of new applicants can be approved.
