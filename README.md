# Communicating Data Findings

# By: Abdulqadir Saieb

## Dataset: Prosper Loan

The Loan dataset from the Peer-Peer Lending marketplace in United States called Prosper. The Dataset contains 113,917 loans data under 81 variables and include information regarding borrowers's financial background, the loan amount, length of the loan, current status of each loan, borrower's annual percentage rate (APR), borrower's interest rate (i), the lender yield on the loan, estimated returns and estimated loss, Prosper rating, credit history, credit score and credit line, borrower income, and plenty more.

## Summary of Findings

### Distribution of data variable(s) of interest. 

The distribution of the variables of my interest were as the following: 
- **Borrower Rate:** The distribution of borrower's rate is almost normally distributed centered around 15% but there is skewness to the right with a peak on about 26% and an outlier on 32%.
- **Borrower APR:** The borower APR is somewhat multimodle, i.e. the distribution is centered on 20% like normal but then there is a small peak at 9% and another high peak on 29% and high count between 35% and 36%. 
- **Term:** Most of the data (about 52000 out of 82000 observations) is on 36 months term (3 years) and the least loan term was 12 months (1 year) which was given to less than 1500 borrowers.
- **Prsper Score:** Most of the borrowers (about 67%) received between 4 and 8 rating scores from Prosper. Less than 17% of the borrowers got high scores of 9, 10, and 11 combined and around 16% got score number less than 4.
- **Prosper Ratng:** Prosper rating  is distributed normally. Almost 22% customers/borrowers got the rating score of 4 but only less than 7% were rated higher rating of 7.
- **Delinquencies:** The distribution of delinquencies (last 7 years) is extremely right skewed, Most of the borrowers are with zero delinquencies and about 3% of the borrowers are with only 1 delinquency and when the number of delinquencies reach 20 and above, there are very few occurrences.
- **Credit Scores:** These trends indicate that most of Prosper's customers have average credit scores and it seems that people with higher credit scores are not interested or not in need to borrow from Prosper and people with very low credit scores are rarely excepted to get loan from prosper.
- **Available Bankcard Credit:** Most counts of credit available via bank card fall in values from 0 to 100,000. Majority of the borrowers who have credit available via bank cards have less than 14,000.
- **Income Range:** The borrowers' income range is left skewed, it could be either the borrowers have stated their income as high or Prosper mostly granted their loans to high income customers. 
- **Loan Original Amount:** The distribution of loan amount is right skewed and most of the borrowers were provided with loan amount between 4000 and 15000 dollars. Obviously, the borrower or an individual will request for amount they needed (for which there is no data in the dataset), but it may also mean Prosper did not want to take risk by granting greater amounts to their customers. 

### Correlations between the variable pairs of my interest are as below:
- There is weak negative correlation between loan terms and the APR but there is almost no correlation with the borrower rate.
- There is weak positive correlation between loan term and Prosper rating and Prosper score.
- The relationship between loan term and the credit score is a weak positive one.
- There is almost no correlation between loan term and the number of delinquencies.
- There is almost no correlation between loan term and available bankcard credit.
- The correlation between loan term and the income range is weak positive.
- The correlation between loan term and the loan amount is a moderate positive correlation, i.e. the loan amount is higher when the loan term is higher and vice versa.
- The correlation between Prosper rating and the borrower APR/ borrower rate is a very strong negative relationship which means the highest the prosper rating, the lowest the APR/ interest rate and the lower the Prosper rating the highest APR/ borrower rate.
- There is a moderate negative correlation between Prosper score and the borrower's APR/ borrower rate.
- There is a moderate negative relationship between the credit score and the APR as well as the interest rate.
- There is a weak negative relationship between the APR + the borrower rate and the number of delinquencies.
- There is a moderate relationship between available bank card credit and the APR/ borrower rate.
- The correlation between APR/ borrower rate and the borrower's income is a weak one.
- There is a moderate correlation between APR/ borrower rate and the loan amount.
- The correlation between Prosper rating and the prosper score is a positive strong relationship.
- The correlation between Prosper rating and the credit score range is moderate positive relationship
- The correlation between Prosper rating and number of delinquencies is a weak negative one.
- There is a moderate positive relationship between Prosper rating and available bankcard credit.
- There is a weak positive relationship between Prosper rating and the income range, i.e. the higher the income range the higher the rating.
- The correlation between Prosper rating and the loan amount is a moderate positive relationship.
- The correlation between Prosper score and the credit score range is a moderate positive correlation.
- The relationship between Prosper score and the number of delinquencies is a weak negative relationship.
- The correlation between Prosper score and available credit via bank card is a moderate positive one.
- The correlation between Prosper score and the income range is a weak positive one.
- There is also a weak positive relationship between Prosper score and the loan amount.
- The correlation between credit score range and number of delinquencies is negative weak relationship
- There is a moderate positive correlation between credit score range and available bankcard credit.
- The correlation between credit score range and the income range is a weak positive one.
- There is a weak positive correlation between credit range and the loan amount.
- There is a weak negative relationship between number of delinquencies and available bank credit.
- There is almost no correlation between delinquencies and the income range as well as the loan amount.
- The correlation between available bankcard credit and the income range as well as the loan amount is a weak positive correlation.
- There is a moderate positive relationship between the income range and the loan amount which means that the higher the income, the larger the loan amount.

 
## Key Insights for Presentation

For the presentation, I first focussed on the distribution of the Borrower APR, the loan term and distribution of lamount. Second, I focussed the correlation between the dataset features, mainly correlation between Prosper rating and the APR, correlation between the APR and/or the borrower's rate and the loan amount, and correlation between the income range and loan amount. 
