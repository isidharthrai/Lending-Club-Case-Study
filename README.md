# Lending Club Case Study

> This project aims to minimize credit loss for Lending Club by analyzing past loan data. Steps include data cleaning, univariate and bivariate analysis to identify patterns related to loan default. Key factors such as loan maturity, borrower grade, and state-wise default rates are considered for informed lending decisions and risk assessment optimization.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Approach](#approach)
* [Conclusions](#conclusions)
* [Recommendations](#recommendations)
* [Technologies Used](#technologies_used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## Problem Statement
* Business Understanding:
    * Lending Club, a consumer finance company which specializes in lending various types of loans to urban customers.
    * There are two primary risks associated with loan approval decisions:
      - Loss of business if loans aren't approved.
      - Financial loss if loans default.
    * The dataset provided contains information on past loan applicants and their loan statuses, aiming to identify patterns
    indicating loan default tendencies.
* Business Objective:
    * Minimize credit loss by identifying risky loan applicants.
    * Understand the driving factors behind loan default to optimize risk assessment and reduce credit loss.
    * By identifying risky loan applicants, the company aims to reduce credit loss and enhance risk assessment processes.
* Data Understanding:
    * The dataset contains complete loan data for all loans issued from 2007 to 2011, including information on loan statuses such as 'Fully Paid' and 'Charged Off’.
    * Referring to the provided data dictionary for a description of the variables included in the dataset.


## Approach
1. Import Libraries & Dataset
2. Data Cleaning
4. Univariate Analysis
5. Bivariate Analysis
6. Conclusion
7. Recommendation


## Conclusions
1. Term of the loan is an important driving factor for default, shorter the maturity of the loan less risky it will be.
2. Grade is also a driving factor for the default, lower the grade higher is the chance of default.
3. Loan given for setting up small business carries the heightes amount of risk followed by loan for renewable energies and education.
4. Following states show higher default ratio:
> MO, FL, NV, AK, SD, NE <br>
> Among these NV and NE shows the heighest default ratio
5. Borrower who made 6 or more inquries in last 6 months shows a higher tendency of default
6. Borrower who has 25 or more open account shows a higher tendency of default
7. Borrower with 90% or more revolving utilization shows a higher tendency of default 
8. If a customer has any public record of bankrupticy then there is a much higher likelyhood of default for that borrower
9. Interest rate may look like as if it is good factor to identify default, however one must not take the higher correlation between high interest rate and default rate for the causation of default. Often finincial institutes charge higher interest rate to high risk customer to compensate for the added risk, and since most of the time it is these high risk customer that default, we see a positive relationship between high interest rate and default, however interest rate is not a leading indicator of default but rather a lagging one.

## Recommendations
1. The company should increase its long term loan exposure with better grade customer and at the same time should reduce its long term loan with the poor graded customer
2. The company should be extra cautious when approving loan for small business, if possible company should ask for collaterals if a poor graded borrower ask for business loan that too for long term
3. For few state like NV and NE where default rate is really high, company may consider closing its business there, given that these states gives a very small proportion of business to the company.
4. Company should add additional checks based on higher number of open accounts, higher revolving utilization while approving a new loan
5. For customers with 2 or more publicly recorded bankruptcy the company should not approve the loan


## Technologies Used
- pandas==2.2.2
- numpy==1.26.4
- seaborn==0.13.2
- matplotlib==3.8.4


## Acknowledgements

- This project was submitted By Sourav Sirohi (5623940) and Sidharth Rai (5760097) as part of an assignment for upGrad and IIITB Machine Learning & AI Program.
- Thanks to Upgrad guiding team and colleagues for giving us the opportunity to explore this project.

## Contact
Created by @isidharthrai - feel free to contact me!