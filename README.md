# Upgrad Lending Club Case Study



## Table of Contents
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Dataset Analysis](#dataset-analysis)
* [Approach](#approach)
* [Case Study Analysis](#case-study-analysis)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Glossary](#glossary)
* [Team](#team)


<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

The core objective of the excercise is to help the company minimise the credit loss. There are two potential sources of credit loss are:

Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates.** Rejecting such applicants will result in loss of business**.
Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss* for the company

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Objectives
The goal is to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA using the given dataset, is the aim of this case study.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

*Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

*Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

*Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

*Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

*Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Approach
- Step 0 - Data Understanding- Identification of Data Quality Issues
- Step 1 - Data Cleaning  - Removing high percentage(70%) of Empty/NA/Duplicate Values
- Step 2 - Dropping Columns based on EDA and Domain Knowledge Such as Columns with Long text, redundant
- Step 3 - Data Type Transformation - Remove % , <1 year etc
- Step 4 - Identify columns with blank values which need to be imputed
- Step 5 - Analysis of the dataset after clean up
- Step 6 - Outlier identification and Handling 
- Step 7 - **Analysis** - Univariate, Bivariate and Derived Metrics Analysis
- Step 8 - **Insights** - Inference and Recommendation
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python 3.12.0](https://www.python.org/download/releases/3.0/)
- [Jupyter Notebook]()
- [JupyterLab](https://jupyter.org/)
- [Anaconda](https://anaconda.cloud/)
- [numpy](https://github.com/numpy)
- [pandas](https://github.com/pandas-dev/pandas)
- [matplotlib](https://github.com/matplotlib)
- [seaborn](https://github.com/seaborn)


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- UpGrad Video By Akashdeep Makkar
- References: https://www.geeksforgeeks.org/what-is-exploratory-data-analysis/



## Contact
Created by [@AshokVashist] & [@bineeshpc] - feel free to contact us!


## Team
* [Ashok Vashist]()
* [Bineesh Panangat]()



