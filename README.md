# Loan-Defaulters-Predictor
This peice of code predicts that a person pays the loan back or not

In this project i have used dataset from Congnitive Class data base which has data of 346 coustomers it is a small amount of data but for practice purpose its perfect 
This data set has 8 attributes based on which we are going to  predict whether he pays his loan or not
They are

Loan_status	       ----->                                          Whether a loan is paid off on in collection

Principal          ----->                                    Basic principal loan amount at the

Terms              ----->                              Origination terms which can be weekly (7 days), biweekly, and and monthly payoff schedule

Effective_date	   ----->                                          When the loan got originated and took effects

Due_date	         ----->                                          Since it’s one-time payoff schedule, each loan has one single due date

Age                ----->                                          Age of applicant

Education	         ----->                                          Education of applicant

Gender	           ----->                                          The gender of applicant

In the intial steps i have shown how to visualize the data before the data preprocessing
In further steps i had processed the data to eliminate any kinds of noices
As you can find there are some categorical value first we had to convert them to numeric values in preprocessing steps
Then i used one hot coding step to convert categorical varables to binary variables and append them to the feature Data Frame

In this project i had performed various Classification Techniques such as 
1. K Nearest Neighbour(KNN)
2. Decision Trees
3. Support Vector Machine
4. Logistic Regression

Evaluated my model using different evaluation matrics such as
1. Jaccard
2. F1-score
3. LogLoss
