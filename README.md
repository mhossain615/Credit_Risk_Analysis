# Credit_Risk_Analysis

## Overview

We are applying machine learning to analyze risk for our client, LendingClub. We are oversampling data using RandomOverSampler and Smote algorithms, and also undersample using ClusterCentroids algorithm. We also compared between BalancedRandomForestClassifier and EasyEnsembleClassifier. This will help us predict credit risk.

## Results 

1. Naive Random Oversampling 

!picture

Based on this picture we can see that our balanced accuracy is 66% furthermore the precision score for high risk is 0.01 and low risk is at 1.00. seems like the scores are both low 

2. SMOTE Oversampling 

!picture2


Based on this picture we can see that our balanced accuracy is 66% furthermore the precision score for high risk is 0.01 and low risk is at 1.00. seems like the scores are both low. which is similar to the first test

3. Cluster Centroid Undersampling

!image3

This picture shows us that out balanced accuracy is a bit lower at 54% But the precision score stays the same at 0.01 and 1.00

4. SMOTEEN (combination of both)

!image4

Based on this, our balance accuracy is at 64% and our precision score is still the same.

5. Balanced Random Forest

!image5

Our balanced accuracy is higher at 78% the precision score is still at 99%


6. Easy Ensemble Classifier

!image6

This is the highest balance accuracy at 93% and precision score at 99%

