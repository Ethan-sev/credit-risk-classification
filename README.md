# credit-risk-classification
# Module 12 Report Template

## Overview of the Analysis

    The purpose of this challenge was to build a model where we can correctly predict high-risk loans as well as healthy loans to maximize 
what is best for lenders. The dataset we used during this challenge had data on loan_size, total_debt, number of accounts and other variables to help determine what is and isnt risky with 0 being a healthy loan and 1 bewing a risky loan. Our dependent variable in this instance was loan_status where we tried to predict the loan status given these factors. 
    This was accomplished by loading the data as a dataframe, then by  seperating our x and y variables. Next I used the train_test_split method where we tested 20% of the data. Next I evaluated the model using a confusuion matrix and ultimatly generating a classification report. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Accuracy: 99%
Precision (healthy loans): 1.00
Recall (healthy loans): 1.00
F1-Score (healthy loans): 1.00
Precision (high-risk loans): 0.86
Recall (high-risk loans): 0.91
F1-Score (high-risk loans): 0.88

With an accuracy of 99% it means that this model does an excelent job at predicting what is and isnt a halthy loan although there
are still some important takeaways. The precision on healthy loans being 1 means that when it is predicted to be a healthy loan, it actually is a healthy loan. 

## Summary

I would argue that you should continue using this logistic regression model as it was very accurate. In summary this was a very effective model 
and pretty accurate for what we are trying to accomplish. 