# Exploratory Analysis of Prosper Loan Data
## by Paul Zebarth


## Dataset

> I used the file 'prosperLoanData.csv' for my analysis. There were 113937 entries and 81 columns. Not all of them were useful for the data analysis but I left them inplace to maintain the data frame. The 'DebToIncome' had outliers at 10.01 to signify the maximum ratio where those people have no income or very little income. I removed this in the dataset because it may be important for exploration.

## Summary of Findings

### Credit Grade Counts vs Borrower Rate

> We will see that credit score does correlate to a lower borrower rate. Credit grades AA, A, B, C and D are all right skewed towards lower borrower rates. Credit E, HR, and NC are left skewed to higher borrower rates.

### Prosper Rating Counts vs Borrower Rate

> We will see that prosper rating does correlate to a lower borrower rate. Credit grades AA, A, B, C and D are all right skewed towards lower borrower rates. Credit E and HR are left skewed to higher borrower rates. By visual inspection we can see the prosper rating has a high effect on the borrower rate as compared to the credit grade. The propser rating has a smaller standard devitation and relates to a small variation in borrower rate. This makes is a good indicator of borrower rate.

### Heat Map of Quantitative Variables Correlation

>We are interested in borrower rate so we will look across the top row or first column and see none of the variables have a strong correlation to borrower rate. However, debt to income ratio has the highest correlation and the amount of investors has the highest correlation to original loan amount out of a comparison of all the variables. Term and original loan amount also seem to be correlated.

### Proportional Loan Usage

>We will see that majority of the loans are being used for debt. This would explain why it was hard to find variables that affect borrower rate. They may use formula to compute borrower rates for different loan usage.

### Borrower Rate vs Days of Loan Delinquency Categorized By Credit Grade/Prosper Rating

>We will see that these facet plots show borrower rate does have a lot of standard values depending on the amount of delinquent days or credit grade/prosper rating and the borrower rate shifts higher the lower the credit grade/prosper rating. This makes sense and we would assume the contract for the loan would have a borrower rate for being delinquent.

### Borrower Rate vs Original Loan Amount By Credit Grade/Prosper Rating

>We will see that from these facet plots the amount each credit grade/prosper rating can secure a loan for changes. The lower the credit grade/prosper rating the lower the maximum loan amount they can secure and the borrower rate shifts higher the lower the credit grade/prosper rating.

## Key Insights for Presentation

>After this analysis it seems the variables used to try and determine how borrower rate was affected did not work. The best indicator we could use to determine borrower rate was the prosper rating. What would have made a better investigation is seeing what variables affect prosper rating.

>It is interesting but not surprising that there were a lot of standard borrower rates for delinquent accounts. Another interesting result in the visuals but not a surprising one is that that credit grade/prosper rating changed the amount in which you could secure a loan. I also discovered that 51.2% of the loans were being used for debt.
