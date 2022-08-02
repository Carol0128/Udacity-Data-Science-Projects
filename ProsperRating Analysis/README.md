# Communicating Data Findings from Prosper Loan Data
## by Carol Ogira


## Dataset

The dataset for this study is from [prosper](https://www.prosper.com/about), a peer to peer lending platform that facilitates matching borrowers with investors and handles the loan servicing on their behalf. The dataset had 81 variables, describing the listing, credit profile of the borrower, amount of loan borrowed and monthly payment, number of investors and percentage funded, among others


## Summary of Findings

The key basis of this exploration was to establish features that could enhance the likelihood of a loan listing getting investors.

The analysis began with some wrangling to ensure good quality and tidiness of the data we would later analyse. This step involved:

- dropping columns that were not necessary in the analysis

- correcting datatypes for all the selected variables.

- appropriately handling the missing and duplicate records

- introducing new columns from the existing, like year, month and waiting days.

Using visualizations to explore the data, the following observations were noted;

> A steady rise in the number of listings was noted from 2011 to 2013, the peak being in 2013, however, the count of listings decreased significantly in 2014. Most loans were borrowed during the first and last months of the year.

> Out of the 48 states present in the dataset, most borrowers were from Carlifornia, New York, Texas and Florida states.

> Most of the loan listings were still running as at time of data collection, that is, of current status. Additionaly,  most of the borrowers fall within an income range of between 50000USD and 75000USD.

> Most of the numerical variables are highly skewed. Number of investors, for instance, has a peak at zero, implying that majority of the listings had very few investors.

> Individuals that borrowed more money equally had to pay more in the monthly installments. Of the money borrowed, the percentage funded by investors had the least correlation with other variables. This indicates that the variation in the other variables had almost no impact on the percantage that was funded.

> Full time employees have the the best prosper score on average, which is quite expected, since they tend to have a stable flow of income to repay loans. Self-employed individuals, however, have the lowest prosper score, with a few outliers having high scores.

> Almost all the loan statuses have an average of about 50 investors, with those with currently running loans having the least number of investors on average.


## Key Insights for Presentation
 
> With the number of loan listings showing a uniform distribution across days of the month, the amount of loan borrowed tend to have repeated upward and downward trends through the days, with the highest amount being at the end of the month.

> Despite the significant increase in amount of loan borrowed through the years, the number of investors per listing has been on a steady decline.

> Comparing the number of investors across income ranges, there is an exponential growth, with income range of above 100,000USD steeper than the other ranges. This implies that borrowers within the high income range get more and more investors with an increase in the amount of loan borrowed.

> There's an interesting observation on individuals whose loans are past due by over 120 days having more investors if their prosper rating is high.
