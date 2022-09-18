# Prosper Loan Data Exploration

## Dataset
The dataset being used for this project is the Prosper loan Dataset, provided by Udacity. There are 113,937 loans in the dataset with 81 features. 
Most variables are numeric and categorical in nature. </br>
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) </br>
The dataset features two main categories:
* Borrower information
* Loan performance information

## Summary of Findings
For this exploratory analysis, my main interest was to analyze the borrowers information for relationship insights with the loans they took. </br>

**Univariate Exploration**

* CA State has the highest borrowers.

* I discovered majority of the borrowers have either employed or fulltime employment

* I discovered that their income mostly ranges from 25,000-74,999 and their monthly income distribution is skewed to the right and they are usually less than 30k. Their income ratio is right skewed as well. 

* The borrower's APR reveals a distribution with different small peaks but one notable and tallest peak occuring at a Borrowers APR of 0.35 , this is the most common or typical Borrowers APR

* Looking at the loan terms, they were either for a period of 12, 36 or 60 months. Most of the loans have a loan term of 36 months.

* I discovered alot of loans were taken in 2013 and worth investigating further.

* Majority of the borrowers are making payments on time per the current loan status


**Bivariate Exploration**

* I discovered that the borrower interest Rate is negatively correlated with the loan original amount, which mean the more the loan amount, the lower the Borrower Rate. 

* I discovered that the loan original amount is positively correlated with the stated monthly income. That is, the higher their stated monthly income, the higher the loan amount borrowed. 

* Borrowers with verified income tend to have a higher average loan amount than borrowers without verified income. 

* Borrowers with income ranging from ($)50,000-100,000+ are majorly homeowners.

* The employed, full-time employed, and self-employed borrowers have higher monthly incomes, obtain higher loan amounts, and enjoy lower Borrower APRs than the part-time, retired, and unemployed borrowers. Borrower rate is slightly lower in Self employed, full-time, unemployed and part -time borrowers.

* There is a strong positive relationship between term and loan amount (longer the term, the larger the loan).

* Employed borrowers tend to take loans of term duration as 36months while Borrowers with full time employment status tend to take loans with term duration of 12months.

* I observed that in 2008-2009 there was a large dip in loan origination that went back up in 2013.

**Multivariate Exploration**

* Loan term did'nt really seem to have effect on the relationship between borrower rate and loan original amount.

* I discovered that People who earn ($)100,000+ and have verified their income tend to get larger loan original
 


## Key Insights for Presentation

For the presentation, I focus on the journey of exploring the features of interest to discover the relationship between the borrowers and the loans they took.
I introduced the features of interest, followed by how they relate to one another and eventually how their correlation is affected by another variable.
Features include: Borrowers' employment status, their income range, stated monthly income and the loan original amount. 

## Limitations

* There were some missing values in some columns which could have messed with the accuracy of the analysis.

* Another challenge was selecting what features of interest to focus on since the dataset had 81 features.
