# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

*The purpose of this analysis is to evaluate the credit risk using logistical regression modeling. The goal was to predict whether a loan is classified as healthy (0) or high-risk (1). Variables used were loan size, borrower income, interest rate, debt-to-income ratio, total debt, etc. 
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
- Accuracy of Model Performance: 99.31%
- Confusion Matrix:
-Classification report:
	- precision for Healthy loans: ~100% 
	- precision for high-risk loans (1): ~87%
	-recall for healthy loans (0): ~100%
	-recall for high-risk loans: ~95%



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

- The logistical regression model performs with high accuracy, with healthy loans being predicted at a higher accuracy rate, although they both are justifiably reliable models. It is more important to predict the 1's. 

If you do not recommend any of the models, please justify your reasoning.
