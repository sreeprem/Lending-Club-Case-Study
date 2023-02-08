# Lending Club Case Study

## Introduction
This assignment will give us an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

-> Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

-> Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

-> Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Business Objectives
-> If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

-> In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Conclusions
From the EDA of the given loan data set we got to known that multiple factors depend on the driving factors. However, according to me some of the impactful factors are .

### Lesser Risk
-> Applicant’s address state FL, NY, TX have some lesser amount of impact of defaulting loan.
-> Higher loan amount increases the risk.
-> From the above graph we get to know that both verified ad non verified peoples loan are equally defaulted, from this we get to that we need to look into the verification process.
-> Loan issue month int the Month Dec, May, Sep

### Higher Risk
-> Loan grade and sub-grade from D to G.
-> Loan purpose increases the risk some purposes are small business, renewable energy, educational.
-> Percentage of defaulters in the term of 36 months is higher than 60 months.
-> Higher interest rate above 13%.
-> People who are in the rented house are more likely to default the loan which is a risk factor.
-> Higher revolving line utilization rate above 58% increase the risk of defaulting the loan.
-> High loan amount and the high interest rate for lower income group.
-> More number of installment and longer repayment term.
-> People who are in the rented house are more likely to default the loan which is a risk factor
-> People who Reside in the CA are more likely to default the loan.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-> numpy
-> pandas
-> matplotlib
-> warnings
-> seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

-> This project was inspired by upgrad lessons


## Contact
Created by [@sreeprem] [@arunabagya] - feel free to contact us!

