# Lending Club Case Study
  This case study focuses on EDA mainly, to understand which parameters are major to detect whether a customer will default loan or not.


## Business Understanding
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- The data set contains the information about past loan applicants and whether they ‘defaulted’ or not. The business objective is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
  1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
        - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
        - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
        - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
  2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Steps followed
1. Data Loading
2. Data Cleaning
3. Univariate Analysis
4. Bivariate Analysis
5. Conclusion


## Conclusions
Major variables affecting the loan getting charged off are as below,
  1. Loan Purpose
  2. Address State
  3. Term
  4. Employment Length
  5. Grade
  6. Interest Rate
  7. Pub Rec Bankruptcies/Pub Rec
  8. Annual Income
  9. Debt to Income Ratio


### Contributors
- Ashish Kumar Singh
- Rohitash Tulyani


##### Worked as part of the EDA Module under Machine Learning and AI course from IIIT-B and Upgrad
