# Module 12 Report Template

## Overview of the Analysis

In this challenge, we were tasked with a building a model that would predict the reliability of a loan or borrower based off of their credit. To do this, we needed to test and train different learning models to assess each model's accuracy in predicting a healthy loan and a risky one. The financial data provided to us as was a histoical lending activity dataset from a peer-to-peer leanding services company and it provided us with some vital information for our analysis. It provided us with features such as the interest rate, the income of the instance, the loan amount, as well any negative bank marks. For the first step, I loaded the data into a dataframe using Pandas and for the second step, I initialized the data into x and y variables and used the train_test_split function to split the data into training data for our logistic regression. Once I created the first model, I created another model using imblearn to resample our split data and deployed similar tactics that I used in the first model. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: I got an accuracy score of 0.95 which means that the model accurately classifies around 95% of all the instances in our dataset.
  * Precision: I got a precision score of 0.85 which means that our model's predictions are right about 85% of the time
  * Recall: I got a recall score of 0.91 which means that our model accurately catches 91% of actual positives, which in our case are actual risky loans.



* Machine Learning Model 2:
  * Accuracy: I got an accuracy score of 0.99 which means that the model accurately classifies around 99% of all the instances in our dataset.
  * Precision: I got a precision score of 0.99 which means that our model's predictions are right about 99% of the time
  * Recall: I got a recall score of 0.99 which means that our model accurately catches 99% of actual positives, which in our case are actual risky loans.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
  The second model seems to perform better since it does better than the first model in every area.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  The second model predicts 1's and 0's better than the first model and one again has a 99% in every aspect which would lead me to believe that it does not matter what we are trying to solve, the second model would still be more accurate than the first model.
