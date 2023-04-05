# Lending-Club-Case-Study
This repository is created, to understand how loan attributes & borrower attributes influence the tendency of landing into default section.


## Contents 

* Introduction
* Data Set used
* Technology used in the case study
* Conclusions


## Introduction


When a person applies for a loan, there are two types of decisions that could be taken by the company:

  ##### 1. Loan Accepted 
  ##### 2. Loan Rejected

 * #### Loan accepted
 If the company approves the loan, there are 3 possible scenarios described below:

 * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

 * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

 * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

 * #### Loan rejected
 
 The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

#### Business objective

We are helping the company to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.


## Data Set Used

we have used the loan data-set with its dictionary to understand and derive to our conclusions. p.s the data set is not included in the part of the repository please, feel free to reach out to me in case you want the file.

## Technologies Used in the case study
- library -- pandas
- library -- numpy
- library -- matplotlib
- library -- seaborn


## Conclusions
Following are the parameters to be considered while giving the loans to avoid the Losses to Lending Clubs
* Verification Status
* Purpose of the loan
* Borrower’s Employee experience
* Borrowers' current resident status
* Interest Rate
* Borrowers with High DTI value


