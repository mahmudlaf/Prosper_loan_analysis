# Prosper Loan Data Exploration

## Dataset

This dataset (prosperLoanData) is a financial dataset for loan processing. 
It is related to the loan, borrowers, lenders, interest rate and other information required from borrowers. 
It contains 113,937 loans with 81 variables. The dataset can be found in the link
[here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000),
with feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000).


## Summary of Findings

In the exploration, I found that most borrowers are home owners, Professinals, employed; with verifiable
income and low debt-income-ratio and majorly from California.

There is a strong relationship between Loan Amount and Monthly Loan Payment. The number of loan application
and Loan Amount also increased over the year.

I also found that there is a negative correlation between borrower APR and Average Credit
Score of borrowers. Moreso, borrowers APR dropped significantly between 2011 and 2014 
for borrowers with/without home.

There are more loan applications during fall (September, October, November and December) 
than any other seasons. However, loan application is at peak at the beginning of the year (January).

Apart from the main variables of interest, I verified the relationship between
Prosper Rating, Percent Funded and being in group. It was realized that At low prosper rating, 
borrowers that belong to groups are more funded than those without group. 
However, at higher ratings, no preference for those that belong to group. 
Borrowers that belong to groups with low prosper ratings get funded than those without group. 
This indicates that those that belong to groups with low prosper rating get preference over those without group. 


## Key Insights for Presentation

For the presentation, my focus of this investigation is to look at those factors 
that affect proper loans, the category of borrowers and the purpose for which they
use the loan. Here, I looked at Employment status, Income Verifiable, 
Credit Score borrower APR, Term of repayment, loan application date, 
borrowers category (Occupation) and listing category. Each of the insights is followed
with clear plots for illustration. 

I started by exploring single variables then bivariate and finally multivariate.
I use bar charts, line plots, pie charts and violin plots. Separate colors for plots with multiple
variables were used for the purpose of clarity.
