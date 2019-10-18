# The Influence of Various Variables on Borrower APR in Prosper Loan Dataset
## by Jamal Taghavimehr

### [Click here to be redirected to my GitHub profile](https://github.com/jamalmehr19)
### [Click here to be redirected to the repository on GitHub](https://github.com/jamalmehr19/Prosper_Loan_Data)

## Introduction

> The dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I will narrow my analysis on 18 variables.

> The link to original dataset: <https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv>

> The description of variables in the dataset: <https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing>

> I mainly focus my analysis on the effect of variables such as Prosper Score on Borrower APR. Before starting the analysis wrangling of data is performed to clean the messy dataset and increase the accuracy of the analysis.

## Summary of Findings

> The strongest relationship was found to be between Borrower APR and Prosper Score for finalized loans (completed and charged_off). The Prosper score up to 5 had a median at 35% APR while after this point the APR proportionally decreased with increasing the score.

> The result was achieved with income range as the median of APR started to proportionally decrease after $1-24,999 bracket. The variability was high for all brackets.

> Charged-off loans were generally higher in borrower APR compared to completed loans. This means that Prosper was already aware of high risk borrowers.

> Computer programmers seem to have highest Prosper scores amongst the top 10 occupations in terms of numbers.


## Key Insights for Presentation

> Prosper is well aware of its borrowers and have done a good prediction of higher risk borrowers along with assigning its own score to the pool of borrowers in a correct manner. As we have seen the highest correlation coefficient was between Prosper Score and Borrower APR.
