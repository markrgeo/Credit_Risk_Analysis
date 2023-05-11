# Credit_Risk_Analysis

Overview of the analysis: 

This exercise was conducted for the purpose of predicting credit risk for individuals seeking loans and credit services. Machine learning was employed for the purpose of sampling and measuring the data that was collected. Different sampling methods were used and accuracy in the measurements were compared across these models to determine which was the most predictive and how best to apply these models.

# Results:

Balanced Random Forest Classifier

Balance Accuracy Score: 0.7877672625306695
Precision: high risk 0.04, low risk 1.00
Recall Scores: 0.91


Combination (Over and Under) Sampling

Balance Accuracy Score: 0.619706620576848
Precision: high risk 0.01, low risk 1.00 
Recall Scores: 0.54


Easy Ensemble AdaBoost Classifier

Balance Accuracy Score: 0.925427358175101
Precision: high risk 0.07, low risk 1.00 
Recall Scores: 0.94


Naive Random Oversampling

Balance Accuracy Score: 0.6293939430565123
Precision: high risk 0.01, low risk 1.00 
Recall Scores: 0.68


SMOTE Oversampling

Balance Accuracy Score: 0.6277008271188627
Precision: high risk 0.01, low risk 1.00
Recall Scores: 0.63


Undersampling

Balance Accuracy Score: 0.5159904274991842
Precision: high risk 0.01, low risk 1.00
Recall Scores: 0.44


Summary

When acknowledging the data our samples were based on it is the Easy Ensemble AdaBoost Classifier that provided the most accurate model for determining the risk of giving loans to people. The scoring on that model showed the most reliable trends. The scoring is between 0 and 1, with a high frequency of scores at approximately 0.9.

If reproducing this test with a data set that is vastly different, another sampling method may be superior, as such if possible it would be in the best interest of the organization offering loans to reproduce this test and take a critical look at how the results compare.
