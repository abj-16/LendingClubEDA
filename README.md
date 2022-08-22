# Lending Club case study
> We will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
> The Lending Club is a company which provides different types of loans online at very less interest rates. If the company is able to identify the risky applicants before sanction of loan, then they can save a huge sum of money.
> The aim of this case study is to use EDA techniques in order to find them by understanding the driving factors responsible for defaulting. The company can use this knowledge for its portfolio and risk assessment.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)
<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
          * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
          * If the applicant is not likely to repay the loan then approving the loan may lead to a financial loss for the company. 
- In this case study, we use EDA to understand how consumer attributes and loan attributes influence the tendency of defaulting a loan and we try to identify those.
- We have been given information about past loan applicants and whether they ‘defaulted’ or not. We identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending at a higher interest rate, etc.
- The given dataset contains the complete loan data for all loans issued through the time period 2007 to 2011 and contains all the details like customer ID, loan ID, annual income, purpose of loan, interest rate etc.

## Conclusions
- First we compared every feature with the loan defaulters, i.e. Univariate analysis and identified the variable which can be used for analysis. 
- Then we did Bivariate analysis to look at the trends and see if it is positive or negatively correlated when compared with one more feature along with defaulter ratio and found some trends.
- Then after we used more than 3 continuous variables and did Multi variate analysis by plotting Heatmap. At the end we found the following variables to be major driving force in defaulting:
1. Loan Amount
2. Interest Rate
3. Annual Income
4. Term
5. Installment
6. Grade
7. Purpose

## Technologies Used
- Python - version 3.10.5
- Numpy library - version 1.20.3
- Pandas library - version 1.3.4
- Matplotlib library - version 3.4.3
- Seaborn library - version 0.11.2

## Contact
Created by [@abj-16](https://github.com/abj-16) - feel free to contact me!
