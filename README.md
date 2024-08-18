**CREDIT RISK CLASSIFICATION**

**(1) Overview of the Analysis-**

**Purpose of the analysis:**

Understanding borrower creditworthiness is important for short term and long term business viability of lending institutions. To that end, using available historical lending information to assist with identifying the creditworthiness of borrowers would be hugely advantageous. This exercise and analysis is intended to train and evaluate a model based on loan risk.


**Data and predictions:**

The dataset used has information on 77,536 unique loans, including details of the size of the loan; the interest rate; the borrower's income; a ration of loan size to income; total debt; loan status; etc.

Predicting whether a loan is high risk or not (whether the loan will be repaid) will be important to the lender.


**Variables and predictions:**



**Order of operations:**

Reading in .csv file 
Creating label set (y)
Creating the features (X)
Splitting the dataset into training and testing datasets for y and X
Fitting a logistic regression model by using the training data (X_train and y_train)
Saving the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model
Determine model performance

**Methods used:**

sklearn train_test_split
sklearn logistic regression and its .fit and .predict functions
confusion matrix
classification report





**(2) Results**

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

**(3) Summary**

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
