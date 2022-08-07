# (Dataset Exploration Title)
## by Idongesit Offiong


## Dataset

The dataset used in this investigation is Prosper Loan dataset from https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, loan original amount and many others.


## Summary of Findings

After the analysis of the prosper loan dataset, the following pattern were observed:

1.Most of the loans in the dataset are current loans some are completed
2.Most loans were taken for a perios of 36 months(3 years)
3.Loans with higher APR tends to be past dues, charged off whereas, completed loans have lower APR
4.There is a strong positive correlation between BorrowerAPR and BorrowerRate
5.The loan original amount does not affect the loan status


## Key Insights for Presentation

For the presentation, I focus on exploring the features of interest to discover which loan features affect the loan status.
I started by introducing the features of interest, followed by how it relate to other variables like original loan amount.
One of the factors that mostly affected the loan status is the borrowerrate/borrowerAPR. Completed loans and running loans all have lower interest rate/APR compared to loans that are past dues etc. It was very surprising to find out that the loan original amount did not have any effect on the loan status.
Another relationship that I looked at in this investigation was between the credit score and borrower rate. There is a negative relationship between the two variables ie, as the credit score increases the borrowerate decreases.
On ploting the original loan amount against the loan term, it was discovered that higher amounts were disbursed for a long term loan and lower amount for short term loan. Similarly, higher loans were disbursed to the employed but lower amounts were disbursed to  the non-employed, part-time or retired. This result was expected as the employment status of a client will determent the repayment the repayment status of a loan. Other parameters in out study that we looked at were original loan amount to the income range of a client in which we found out that the income of a client determines the loan amount disbursed.
