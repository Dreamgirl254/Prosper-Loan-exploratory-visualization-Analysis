# Prosper Loan Data Exploration and Analysis
## by Donna Fedha Obong'o


## Dataset
> From the prosper website we know that Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than $22 billion in loans to more than 1,350,000 people.  

> The dataset being explored is a loan dataset containing 113,937 loans(rows) and with 81 variables(columns),some of these variables are Borrower rate(Interest rate),term(how long the loan has been taken for), prosper score also known as the risk rating and more. It is important to note that each loan has a listing key which is a unique key for each listing, same value as the 'key' used in the listing object in the API.  

>This dataset can be downloaded here: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv


## Summary of Findings  

During the exploration, various **discoveries** were made: 

  + A higher number of people opt to take loans for 36 months.  
  + Borrower rate and borrower APR as somewhat similar since they perfectly correlate with each other. Borrower APR is basically the borrower rate and other costs involved during borrowing.  
  + Most borrowers take loans for debt consolidation.  
  + The more the years of work experience the lesser the loans. Most borrowers have low work experience, with 0,1 and 2 years work experience being the most.  
  + Most borrowers have an income range of $25,000-$74,999.  
  + CA which stands for California, is the state with the highest number of borrowers.  
  + Most borrowers are employed.  
  + According to the prosper score high risk borrowers have a higher estimated effective yield.  
  + Self-employed workers have the highest risk rating while full-time workers have the lowest risk rating.
  + High risk borrowers have a higher lender yield.  
  + Low risk borrowers have a lower interest rate.  
  + The number of defaulted loans per year decreased as time went by.
  + Highest loss was made in 2007 even after recovery.  
  + More often homeowners have a high prosper score(low-risk) compared to non-homeowners.  
  + Borrower rate and APR highly correlates negatively with the prosper rating and prosper score. 

> A big part of the final presentation will focus on the Borrower rate, Borrower APR and the Prosper Score.


## Key Insights for Presentation
  
> Prosper score has the strongest relationship with borrower rate and borrower APR. As the prosper score increases the borrower rate and APR decreases,this shows that low risk borrowers have a low intererest rate compared to high risk borrowers.  

> The relationship between the Borrower APR and Lender yield are positively correlated. This means that as the borrower rate increases then the lender yield also increases. It is important to note that the higher the prosper score the lower the lender yield and borrower APR. This can be seen in the plot for LenderYield vs BorrowerAPR  vs ProsperScore.