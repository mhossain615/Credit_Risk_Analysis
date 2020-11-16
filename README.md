# Credit_Risk_Analysis

## Overview

We are applying machine learning to analyze risk for our client, LendingClub. We are oversampling data using RandomOverSampler and Smote algorithms, and also undersample using ClusterCentroids algorithm. We also compared between BalancedRandomForestClassifier and EasyEnsembleClassifier. This will help us predict credit risk.

## Results 

1. Naive Random Oversampling 

 [![image1](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image1.JPG)

Based on this picture we can see that our balanced accuracy is 66% furthermore the precision score for high risk is 0.01 and low risk is at 1.00. seems like the scores are both low 

2. SMOTE Oversampling 
 [![image2](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image2.JPG)


Based on this picture we can see that our balanced accuracy is 66% furthermore the precision score for high risk is 0.01 and low risk is at 1.00. seems like the scores are both low. which is similar to the first test

3. Cluster Centroid Undersampling

 [![image3](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image3.JPG)

This picture shows us that out balanced accuracy is a bit lower at 54% But the precision score stays the same at 0.01 and 1.00

4. SMOTEEN (combination of both)

 [![image4](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image4.JPG)

Based on this, our balance accuracy is at 64% and our precision score is still the same.

5. Balanced Random Forest

 [![image5](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image5.JPG)

Our balanced accuracy is higher at 78% the precision score is still at 99%


6. Easy Ensemble Classifier

 [![image6](https://github.com/mhossain615/Credit_Risk_Analysis/blob/main/Images/image6.JPG)

This is the highest balance accuracy at 93% and precision score at 99%

## Summary 

Based on these datasets, most of these datasets are similar to one another. all were percise as well. one thing to note is that the high risk for all of these datasets are low so that might bring upon issues in the future. it may be useful to use the last two models but it still feels like inclusive data all around in order to have a more better prediction in general.

 
