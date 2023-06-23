# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy: Accuracy score is 0.99. This means that approximately 99% of the transactions in the test data were accurately categorized by the model.
  * The precision for the 0 values is 1.00. That means that out of all the times that the model predicted a testing data observation to be the value 0, 100% of those predictions were correct.
  * Model 1 Recall is .91


* Machine Learning Model 2:
  * Description of Model 2 Accuracy: : Accuracy score is 0.99. 
  * The precision for the 0 values is 1.00.
  * The recall value is 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Both models are recommendable for predicting people with healthly loans but the second model is better at finding high risk borrowers. The second model does have lower precision but it is better able to identify risky loans. 