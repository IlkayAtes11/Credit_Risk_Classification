# Credit Risk Classification ( Supervised Machine Learning Model)

## Overview of the Analysis

* The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.
* A dataset of historical lending activity from a peer-to-peer lending services company was used. 
* Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk. 
* Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
* Describe the stages of the machine learning process you went through as part of this analysis.
* Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end their results -which was gathered with scikit-learn library- were compared.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model with Original Data
 
![Balanced Accuracy Score](./Images/balanced_accuracy_score_1.JPG)
![Classification Report](./Images/classification_report_1.JPG)

* Logistic Regression Model with Randomly Oversampled Data

![Balanced Accuracy Score](./Images/balanced_accuracy_score_2.JPG)
![Classification Report](./Images/classification_report_2.JPG)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


Using Machine learning, we can effectively train and model data to prevent fraud based on data collectved from customers.

oversampling the training model, we managed to get an result that was had a high accuracy of predicting risky loans.

False positives where users are flagged as wisky, but are actually healthy will mean that certain customers will be blocked from taking out legitimate loan, sacrificing some of the bottom line revenue, however, predicting the frauduelent activity is more iportant because the purpose of this analysis is to reduce the amount of risky loans and there is a high likelyhood that the risky loans costly.
