# Module 12 Report Template

## Overview of the Analysis

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.
* A dataset of historical lending activity from a peer-to-peer lending services company was used. 
* 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).


The "target/dependant variable" or "y value" was the loan_status indicating if a loan was at risk. While the feature set (Independent Variable) included additional data points collected such as loan_size
The financial information was based on several datat points gathered including;

loan_size
interest_rate
borrower_income
debt_to_income
num_of_accounts
derogatory_marks


* Describe the stages of the machine learning process you went through as part of this analysis.
* Results from Logistic Regression Model and Resampling Model have been compared.



Implement machine learning models.
Use resampling to attempt to address class imbalance.
Evaluate the performance of machine learning models using scikit-learn library.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


Using Machine learning, we can effectively train and model data to prevent fraud based on data collectved from customers.

oversampling the training model, we managed to get an result that was had a high accuracy of predicting risky loans.

False positives where users are flagged as wisky, but are actually healthy will mean that certain customers will be blocked from taking out legitimate loan, sacrificing some of the bottom line revenue, however, predicting the frauduelent activity is more iportant because the purpose of this analysis is to reduce the amount of risky loans and there is a high likelyhood that the risky loans costly.
