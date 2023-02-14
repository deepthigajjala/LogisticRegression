🎈🎈#BUSINESS PROBLEM🎈🎈

LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

The data science team at LoanTap is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

LoanTap deploys formal credit to salaried individuals and businesses 4 main financial instruments:

Personal Loan
EMI Free Loan
Personal Overdraft
Advance Salary Loan
This case study will focus on the underwriting process behind Personal Loan only

❤️❤️MY ANALYSIS❤️❤️

1. Imported the data and did some basic data pre-processing steps.
2. The dataset has 396030 rows and 27 columns.
3. This dataset has discrete and continuous columns.
4. Through the plots of continuous variables I can conclude that there are outliers.
5. From the plots discrete varaiables I can conclude that
          There are more people who took loan for 36 months
          There are more people with Grade B
          There are more people who has Employement_length more than 30 years
          There are more people with Home_ownership Mortguage
          There are more people with Verification_status as verified
          There are more people with loan_status as Fullu_paid
          There are more people with application_type as Individual
6. As columns has different unique values I did Label encoding and Target Encoding.
7. By using Spearman Correlation I removed the highly correlated columns.
8. Some of the columns has null values I removed them as the count is very less.
9. I splitted the data into training and test data
10. By using IQR Method I removed outliers.
11. I ran Logistic model and decided best value for lambda.
12. By using the best lambda value I trained the model and tested it.
13. I got training score as 0.882and test score as 0.881.
14. I calculated the weights of each column.
15. ROC Curve and confusion matrix looks fine.
