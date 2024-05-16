# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to develop
* Our financial information consisted of loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status. Our goal was to predict whether a loan was healthy (which was assigned a 0) or high-risk (which was assigned a 1).
* Using LogisticRegression we wanted to predict loan_status.
* The stages of the machine learning process I went through as part of this analysis.
    * I imported lending_data.csv and then put it into a pandas dataframe.
    * y was set to the loan_status column and X ws set to the rest of the columns in the dataset.
    * I then utilized train_test_split() to obtain the X_train, X_test y_rain, and y_test.
    * I then ran a train_test_split() to get X_train, X_test, y_train and y_test.
    * I then used the X-test to create predictions. Then I created a confusion matrix.

## Results

* Machine Learning Model 1:
    * Accuracy: The logistic model has an overall accuracy of 99%. It will predict the loan status 99% of the time.
    * Percision: Healthy loans are predicted correctly 100% of the time. High-risk loans only have an 85% accuracy. This is probably because
    * Recall scores: 99% of healthy loans are labeled correctly compared to 91% of high-risk loans.

## Summary
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

The logistic model performs the best because it achieves the highest accuracy, strongest precision and recall scores.

