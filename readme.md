# Diamonds Data Exploration

## Dataset

This dataset contains 113,937 loans with 81 variables on each loan, 
including loan amount, borrower rate (or interest rate), current loan status, 
borrower income, and many others. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) 
and a detailed description of all the features can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/).


## Summary of Findings

In the exploration, I found that there was a strong positve correlation
between the EstimatedEffectiveYield, BorrowerAPR and BorrowerRate and
also the LoanOriginalAmount and the MonthlyLoanPayment are highly correlated.
Another thing we found out is that loans with Chargedoff & Defaulted status tend 
to have a higher BorrowerAPR on average and that that the BorrowerAPR is less for 
borrowers with the higher ProsperRating. Also found out that borrowers with 
Part-time EmploymentStatus have the lowest MonthlyLoanPayment on average and that
those who have the lowest ProsperRating also have the lowest MonthlyLoanPayment
and that the defaulted & charged off loans have the lowest StatedMonthlyIncome
on average.

Also, as expected, the majority of the borrowers who are Employed or Full-time 
have a verifiable source of income, meanwhile most of the Self-employed borrowers 
have no verifiable source of income. Also, we found out that there's a negative 
correlation between the BorrowerAPR and the LoanOriginalAmount.

Last but not least, comparing different listing categories, we find that most of 
the defaulted and charged off loans are listed as Not Available, that could be 
either due to missing data or that the borrower didn't provide a reason for the loan.


## Key Insights for Presentation

For the presentation, I focus on just the influence of different variables
such as the Original Loan Amount, ProsperRating on the BorrowerAPR and
how the BorrowerAPR might affect the loan status.