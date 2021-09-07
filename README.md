*# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is to learn about supervised machine learning. We used credit risk for our project to determine in various machine learning techniques on how should we accept/decline loans based in different dependent variables and through analyzing our confusion matrix results to determine how accurate, our predictions were.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

* Naive Random Oversampling
** Balanced Accuracy Test: 65.0%
** Precision Score: high_risk 1%; low_risk 100%
** Recall Score: high_risk 69%; low_risk 60%

* SMOTE Oversampling
** Balanced Accuracy Test: 66.0%
** Precision Score: high_risk 1%; low_risk 100%
** Recall Score: high_risk 63%; low_risk 69%

* Undersampling 
** Balanced Accuracy Test: 52.0%
** Precision Score: high_risk 1%; low_risk 100%
** Recall Score: high_risk 69%; low_risk 40%

*Combination (Over and Under) Sampling
** Balanced Accuracy Test: 66.0%
** Precision Score: high_risk 1%; low_risk 100%
** Recall Score: high_risk 75%; low_risk 58%

*Balanced Random Forest Classifier
** Balanced Accuracy Test: 75.0%
** Precision Score: high_risk 3%; low_risk 100%
** Recall Score: high_risk 63%; low_risk 89%

* Easy Ensemble AdaBoost Classifier
** Balanced Accuracy Test: 93.0%
** Precision Score: high_risk 1%; low_risk 100%
** Recall Score: high_risk 92%; low_risk 94%

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

The best Accuracy test was the Easy Ensemble AdaBoost Classifier and might be due to the technique of comining weak learners and bringing strong learners to the table. My opinion it is a great idea in the loan applications because the dependent variables isnt a big list which helps create strong learners quickly. The model trains itself to correct the model for better accuracy.