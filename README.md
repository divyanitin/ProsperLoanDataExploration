# ProsperLoanDataExploration
# By Divya Nitin Naidu

## Dataset

The Dataset contains 113,917 loans, each loan has information on each borrower's annual percentage rate (APR), status, borrowed amount, debt, etc. Variables with missing values were dropped to make the Dataset more accurate. Outliers were also removed to provide more reliable Data. This investigation will be analyzing factors that could influence borrower's APR and what loans were taken by what type of borrowers.

The dataset can be download [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000)


## Summary of Findings

In the exploration, I found that the borrower APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The borrower APR also decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. 

Outside of the main variables of interest, I found that the loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term. I also found that borrowers with better ratings have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. There is a interaction between categorical term and Prosper rating features. Proportionally, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers. For loan amount, there is a interaction between term and rating. With better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.

## Key Insights for Presentation

First, histogram plot were created to visualize the distribution on borrower's APR percentage. After exploring all possible variables related to BorrowerAPR. ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated. The third plot created multiple scatter plots (BorrowerAPR vs ProsperScore) on different letter ratings.
