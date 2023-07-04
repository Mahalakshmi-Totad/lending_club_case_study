# Lending Club Case Study

> Analyse Data from a csv containing information about the past loan applicants and try to identify patterns that indicated if a person is likely to default, which can be used for taking actions such as denying loans , reducing the loan amount or lending at higher interest rates to risky applicants etc. Using EDA to understand the customer attributes and loan attributes and derive relavent conclusions from it.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- In this project we aim to analyse the data provided from a csv that contains information about the past loan applicants and attempt to identify patterns in customer and loan attributes that may contribute to them defaulting. We will attempt to analyse the data using python and plot charts and see if any patterns can be identified from the information.

- Lending loans to ‘risky’ applicants is the largest source of financial loss for the company.Borrowers who default cause the largest amount of loss to the lenders.Hence it is very important to identify these individuals from the pool of applicants in future.
- Assuming we will be considering new applicants for the purpose of evaluation in future based on the trends found from historical data

###steps Taken :

- Data Cleaning
- Univariate Analysis
- Bivariate Analysis
- Drawing Concusions from Analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

On observing the trends from the data set obtained the following factors should be considered by the bank before approving loans :

- If customer is having home ownership as renting or mortgage , and with the annual income in the range 30-60k , it can be a high risk profile
- If customers purpose for loan is home improvement and annual income is around 80k, huge loans should not be approved
- Longer term loans with installments of 1000-2000 is a high risk
- Bank should reduce providing loans between 6K - 9K for the states for CA, NY and FL
- Bank should discourage providing loans for lower grades
- Banks issue a lot of loans to people with 0 public records and 2-10 open credit line , and which ideally indicate low risk, but according to the data have a high number of defaulters
- Bank should discourage sanctioning Loan amount more than 30k with rate of interest between 16-19% as it shows high number of defaulters
- Banks should discourage approval of loans if Inquiry for Loan in the last 6 months greater or equal to 6
- If the DTI range of 12-24% we found that there is a high likelihood they are taking loan for debt consolidation , which increases risk

Hence we can conculde that customers who exhibit two or more of the above mentioned factors would pose a high chance of defaulting and can be used as factors to consider when approving loans for future customers.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python
- numPy
- Pandas
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad
- This project was based on EDA as part of PG Programme in ML and AI May 2023.

## Contact

Created and worked on by Mahalakshmi Totad[@Mahalakshmi-Totad] and Vivek P Rajeev[@Zelphire]
