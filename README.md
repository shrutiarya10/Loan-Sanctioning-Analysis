# Loan-Sanctioning-Analysis

### Problem Statement
You work for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision: 
* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
*  If the applicant is not likely to repay the loan, i.e. he/she is likely to default.

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. So, the busi business problems are solved using EDA.
 
 
### Analysis :
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

When a person applies for a loan, there are two types of decisions that could be taken by the company: 
- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
   - Fully paid: Applicant has fully paid the loan (the principal and the interest rate) 
   - Current: Applicant is in the process of paying the installments, i.e. the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted'. 
   - Charged-off: Applicant has not paid the installments in due time for a long period of time, i.e. he/she has defaulted on the loan. 
 
2. Loan rejected: The Company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset) 
 
 In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.
