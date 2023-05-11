# Credit_Risk_Analysis

Overview of the analysis: 

This exercise was conducted for the purpose of predicting credit risk for individuals seeking loans and credit services. Machine learning was employed for the purpose of sampling and measuring the data that was collected. Different sampling methods were used and accuracy in the measurements were compared across these models to determine which was the most predictive and how best to apply these models.

# Results:

Balanced Random Forest Classifier

![Balanced Random Forest Classifier - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/9c30b1bd-ee44-4d55-95ad-121f4f9b5e85)
![Balanced Random Forest Classifier](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/df029663-8b95-4aff-9472-83c457f17940)

Balance Accuracy Score: 0.7877672625306695

Precision: high risk 0.04, low risk 1.00

Recall Scores: 0.91


Combination (Over and Under) Sampling

![Combination Sampling - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/8c20113d-2dae-4295-bf80-a95e0dc325dd)
![Combination Sampling](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/03347d8e-01d8-4f80-be6e-0c938af7277b)

Balance Accuracy Score: 0.619706620576848

Precision: high risk 0.01, low risk 1.00 

Recall Scores: 0.54


Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/ac398687-f60e-4d50-9f85-5c0d2d0da714)
![Easy Ensemble AdaBoost Classifier](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/a55ecbd7-907a-40a0-887b-5ee1bd95456d)

Balance Accuracy Score: 0.925427358175101

Precision: high risk 0.07, low risk 1.00 

Recall Scores: 0.94


Naive Random Oversampling

![Naive Random Oversampling - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/8431c484-ab38-47ed-849d-502d381ef5a8)
![Naive Random Oversampling](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/e2829f8e-9c4a-413d-b222-9b6c77cf70d6)

Balance Accuracy Score: 0.6293939430565123

Precision: high risk 0.01, low risk 1.00 

Recall Scores: 0.68


SMOTE Oversampling

![SMOTE Oversampling - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/70b0cf59-7543-454e-9e12-d10da4503c01)
![SMOTE Oversampling](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/ccac6deb-1c1f-46f8-b87c-0ac80acce7c5)

Balance Accuracy Score: 0.6277008271188627

Precision: high risk 0.01, low risk 1.00

Recall Scores: 0.63


Undersampling

![Undersampling - balance score](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/067da9f7-dbb9-4c1d-94db-cd1f0c940926)
![Undersampling](https://github.com/markrgeo/Credit_Risk_Analysis/assets/119453505/2b10c16d-8d17-43fc-8638-f3300f20be4a)

Balance Accuracy Score: 0.5159904274991842

Precision: high risk 0.01, low risk 1.00

Recall Scores: 0.44


Summary

When acknowledging the data our samples were based on it is the Easy Ensemble AdaBoost Classifier that provided the most accurate model for determining the risk of giving loans to people. The scoring on that model showed the most reliable trends. The scoring is between 0 and 1, with a high frequency of scores at approximately 0.9.

If reproducing this test with a data set that is vastly different, another sampling method may be superior. In such a case, if possible it would be in the best interest of the organization offering loans to reproduce this test and take a critical look at how the results compare.
