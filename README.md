## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, this projected sought to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Also, using a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, this projected compared two new machine learning models that reduced bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results

![Naive_Random_Oversampling](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.png)

- The balanced accuracy score is 64%
- The precision high risk is approximately 1% with 61% sensitivity

![SMOTE_Oversampling](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/SMOTE_Oversampling.png)

- The balanced accuracy is 62%
- The precision high risk is approximately 1% with 61% sensitivity

![Undersampling](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/Undersampling.png)

- The balance accuracy score is 51%
- The precision high risk is approximately 1% with 57% sensitivity

![Combo_Over_Under](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/Combo_Over_Under.png)

- The balanced accuracy score is 61% 
- The precision high risk is approximately 1% with 69% sensitivity

![Balanced_Random_Forest](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest.png)

- The balanced accuracy score is 78%
- The precision high risk is approximately 4% with 67% sensitivity

![Easy_Ensemble_AdaBoost](https://github.com/doloresbryant83/Credit_Risk_Analysis/blob/main/Easy_Ensemble_AdaBoost.png)

- The balanced accuracy score is 93%
- The precision high risk is approximately 9% wit 92% sensitivity 

## Summary

Each of the models used to perform the credit risk analysis have their strengths and weaknesses.  What is concerning is that a number of the models have low balanced accuracy score.  The exception is the Easy Ensemble AdaBoost model, which further has a higher precision in comparison to the other models.  I would recommend that the bank precede with caution if any of the models are chosen.