# Exploring Annual Percentage Rate (APR)

## by Garett Hansen


## Dataset

This data was provided by marketplace lending company Prosper and is comprised of 113,937 individual loans across a wide range of loan types (i.e. home improvement, auto, student, etc). While 81 different variables are attributed to each loan (i.e. interest rate, loan amount, credit rating, etc), only a subset of those variables were analyzed. The purpose of this project is to utilize summary statistics and different forms of visualizations in order to understand the relationships between the aforementioned loan variables.

The original dataset can be found here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000


## Summary of Findings

I began this project by choosing a handful of variables (income range, credit score, and loan size) and reviewing their individual characteristics. I then compared APR to each independent variable (univariate) before moving on to bivariate and multivariate analyses.

During the course of this project, I discovered several different findings with some surprises along the way. The higher the reported income, the lesser the APR. This makes sense as those with higher incomes may present lower risk than those with lesser income. However, there is some strangeness here as those with 0 reported income were associated with low APR, but those labeled as unemployed were associated with high APR. When income range is combined with credit score, the differences in APR for different sets of borrowers became very apparent. While high earners with excellent credit scores were favored with the lowest rates, those with poor credit scores, even among high earners, experienced higher APR.

A large portion of the loans provided were small to mid-sized loans (less than $12,000), with smaller loans being associated with higher APR than larger loans. When combining loan size with income range, those with higher income tended to experience lesser APR, with the exception of very small loans (less than $4,000). 


## Key Insights for Presentation

For the presentation, I chose to start off with the overall distribution of APR's across the dataset in order to display the range of APR's borrowers paid. As anyone who has applied for a loan of some sort is aware, APR is determined by multiple factors. In order to present the interesting relationships between variables and how they impact an borrower's APR, I then discuss the two multivariate plots of my analysis (1) APR vs income range and credit rating, and 2) APR vs income range and loan size).

## Sources

Credit score data from Experian (https://www.experian.com/blogs/ask-experian/credit-education/score-basics/what-is-a-good-credit-score/)