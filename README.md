# Lending Club Case Study
This case study to help a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
 - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
   
In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The Loan dataset given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. The key areas to identify:
- Determine the characteristics and patterns of borrowers likely to default, labeled as "charged-off.“
- Analyze the factors that strongly correlate with loan defaults, such as salary, loan term, and home ownership status.
- Utilize insights to refine approval criteria, reduce credit loss, and improve overall portfolio quality.
- Assess variables that can justify higher interest rates for risky borrowers to balance business objectives and risk mitigation.
- Equip the company with actionable insights for better customer segmentation and tailored lending strategies.

## Conclusions
- Risk-Based Interest Rates: Increase interest rates for discretionary purposes and borrowers with low income or work experience.
- Income-to-Loan Cap: Limit loans to a maximum of 40% of the borrower's annual salary.
- Enhanced Regional Policies: Implement state-specific credit policies for high-risk states.
- Targeted Grading Recalibration: Reassess loan grades to reflect updated risk patterns.
- Promote Shorter Loan Terms: Encourage 36-month terms through better rates or benefits.
- Improved Credit Checks: For renters and less experienced applicants, introduce stricter financial screening. 
- Reduce exposure to high-risk loan purposes such as debt consolidation and small business loans.

## Technologies Used
- python - v 3.12.14
- numpy - v 1.26.4
- pandas - v 2.2.2
- seaborn - 0.13.2
- matplotlib - 3.8.4

## Acknowledgements
Give credit here.
- This project was inspired by the course in Machine Learning and AI with Upgrad facilitated by IIIT Bangalore.

## Contact
Created by @abirla & @amlan20 - feel free to contact us!

