# Credit_Risk_Analysis

## Overview
The purpose of this project is to employ different techniques to train and evaluate models with unbalanced classes in credit risk. This was achieved by using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling using a credit card dataset from LendingClub. 

## Results 
* The *Naïve Random Oversampling* results shows that the balanced accuracy test is 64% with a low high-risk positivity of 1% and a recall of 69%.
 ![naive_random_oversampling](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/naive_random_oversampling.png?raw=true) 

* The *SMOTE Oversampling* model shows an accuracy score of 66% with a low high-risk positivity of 1% and a recall of 69% overall.
![SMOTE_oversampling](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/SMOTE_oversampling.png?raw=true)

* The *Undersampling* model shows an accuracy score again of 66% with a precision of 99% and a recall of 40% overall.
![undersampling](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/undersampling.png?raw=true)

* The *Combination (Over and Under) Sampling* model shows a balanced accuracy score of 54% with a precision of 99% and a recall of 57% overall.
![combination](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/combination.png?raw=true)

* For the Ensamble Learners the *Balanced Random Forest Classifier* model shows an accuracy score of 77% with a precision of 99% and a recall of 88% overall.
![balanced_random_forest_classifier](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/balanced_random_forest_classifier.png?raw=true)

*The * Easy Ensemble AdaBoost Classifier* model shows an accuracy score of 92% with a precision of 99% and a recall of 94% overall.

![easy_ensemble](https://github.com/adecoste2/Credit_Risk_Analysis/blob/main/Resources/easy_ensemble.png?raw=true)

## Summary
In the first four resampling models the dataset was over sampled, under sampled and a combination of both undersampling and oversampling to determine which model was best at predicting which loans are highest risk. The next two models using ensemble classifiers, where used to determine which loans were high risk and which loans were low risk. 
The highest accuracy ratings came from the models using the ensemble classifiers (the last two models created). The best results though, came from the last model – the Easy Ensemble AdaBoost Classifier because of it’s high accuracy score and best balance of precision and recall scores. 
