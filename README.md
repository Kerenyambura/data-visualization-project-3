# Loan Data Exploration 
## by Keren Wang'ombe


## Dataset

> The dataset contains information about loans from Prosper. Originally there were 113,937 entries in the dataset with 81 columns.Not all columns were needed in the analysis and others were dropped. Most variables are numeric in nature. After picking the columns that I neededed there are 16 columns. The columsn were reduced to make it easier to work with the columns that I needed. 
> I also changed the LoanOriginationDate into a date time format.

## Summary of Findings

### Univariate Exploration

> In the exploration, I found the evidence of a strong relationship between borrowers APR and borrowers rate. They had the same plot pattern which is normal because Borrower Rate plus other charges make up the Borrower APR. The loan amount collected was widely distributed, between 1000 and slight above 30000 dollars. The prosper Score distrbution showed that it is multimodal, with score 4,6,8 dominating the population. Prosper Rating distribution showed C was the most common rating among the borrowers and the least was AA. The employment status distribution showe that the  majority of individuals that applied for the loans are employed and the least being retired individuals. The homeowners distribution was evenly distributed in the population. Large numbers of the borrowers are of the high income range earners. using the log scale, the borrowers who are currently on the loan plan are the highest, followed by those who have completed the loan Majority of the loan was collected for debt consolidation.

### Bivariate Exploration

>Using a bar plot to get the average borrower APR distribution per year, it shows that 2011 had the highest APR. 2006 had 0.2% with a slight fall to 2007 and a gradual increase till 2011 which was the highest APR % rate about 0.25% and a steady fall occurred from 2012 to 2014.

> Using a violin plot to show the relationship between borrower rate and employment stsus and borrower rate and income range, it was clear that employment does not generally mean a lower rate the unemployment rate has a larger median rate and a greater frequency concentration above the median

> Using a correlation heatmap to show the relationship between income range and if the borrower is a homeowner, the plot showed that most loan borrowewrs were indeed homeowners. 

>using a boxplot to show the relationship between borrower apr and prosper score, the plot showed that the higher the ratings, the lower the borrower APR which can be interprated to mean to have a good rating, ones APR must be below 0.1%.

### Multivariate Exploration
> Using a braplot to show the relationship between yearly borrower rate and if the individual was a homeowner, the plot showed that homeowners do have a slightly lower rate that non-homeowner.

> Using a multivariate boxplot to investigate the relationship between yearly borrowers rate and prosper score and the result showed that for score 5 or above, homeowners have lower rate, and for scores below 5, homeowners have similar or higher borrowing rate.

>Showing how Borrower APR affect the loan range and Homeowner relationship with an heatmap to look further into the bivariate plot, the disribution shows that The borrowers APR had no effect on the home owner relationship. Although, the loan amount had an inverse relationship with borrower APR.

>Looking further into the clusterd bar chart in the bivariate while adding Term to the distribution, the plot shows that the longer term(5 years) the higher the borrower APR which means the longer the term the individual collect the loan the higher their APR gets.


## Key Insights for Presentation

> The first multivariate showed that the higher the APR, the lower the loan collected and the homeowner had no influence on the loan amount range. However, using the term shows the longer the term which loan was collected no matter the amount, the higher the APR gets.