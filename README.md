# (Loan Data Exploration)
## by (Samah Alsulami)


## Dataset

Our goal is to explore a sample of Prosper's loan data, and This document explores a dataset containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

This exploration aims to obtain a clear picture of the status of loans and the factors affecting them, and to understand the motives of borrowers. 
- the borrower's interest rate follows a multi-modal distribution. There are peaks in the interest rate, most of which range between 0.1 and 0.2. But there is a peak centered between 0.34 and 0.36. We also note that loans with an interest rate greater than 0.44 are few.
- The states that have the biggest numbers of loans, which are: California, Texas, New York and Florida
- The majority of loans are current. And because the number of loans in the dataset is huge, the number of completed loans were approximately 38,000, and chargedoff loans were about 11,000 loans
- There is an inverse relationship between a borrower's interest rate and his income range.
- Negative correlation between the loan amount and the interest rate.
- the interest rate is determined by the Employment status of the borrower, because the employee gets a monthly income that enables him to obtain a high loan amount, and thus the interest rate decreases.
- As for understanding the motives of the borrowers, the result was surprising. We found that most of the borrowers ask for the loan in order to Debt consolidation!!




## Key Insights for Presentation

For the presentation I will focus on showing the impact of the four factors on the interest rate
1- Income Range   2- Loan Original Amount   3- Prosper Score   4- Prosper Rating
- I will start by introducing the interest rate variable followed by its distribution.
- I will use a scatter plot to show the relationship between the loan amount and the interest rate
- I will show the correlation between the employment status of the borrower and the amount of the loan and their effect on the interest rate
-  I will show the correlation between loan amount, interest rate, and Prosper score in a multivariate scatterplot
- Finally, I will show the word Cloud showing the distribution of the states with the largest number of loans