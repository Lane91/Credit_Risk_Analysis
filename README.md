# Credit_Risk_Analysis

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I created six machine learning models and evaluated each model. I will show the results of each model and finally compare all six to see which models would be best to predict credit risk.

## Results

# Naive Random Oversampling

![Random Oversampling](https://user-images.githubusercontent.com/95251140/167316500-8e1a1afb-d330-42dc-9e3f-1c175a5c0dd8.png)

Balanced accuracy score

![oversampling balanced acc score](https://user-images.githubusercontent.com/95251140/167316780-24781b95-6a0e-45c1-bd13-52b85760ec8c.png)

# SMOTE OverSampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/95251140/167316525-bb70827e-5f8d-46e8-9284-6a5b2737f125.png)

Balanced accuracy score

![SMOTE balanced acc score ](https://user-images.githubusercontent.com/95251140/167316831-98c32ef5-88d4-4ff1-aeb3-2dd8851ff802.png)

# Undersampling Cluster Centroid

![Undersampling Cluster_Centroids](https://user-images.githubusercontent.com/95251140/167316559-18f5cd22-be7c-474f-b309-4696e804de31.png)

Balanced accuracy score

![undersampling cluster balanced acc score ](https://user-images.githubusercontent.com/95251140/167316878-648ea99c-e2ef-4028-84dc-8bb80b0c048a.png)

# Over and Under Sampling SMOTEENN

![SMOTEENN Combo](https://user-images.githubusercontent.com/95251140/167316593-cc76be39-ac31-4f09-9720-23bfcefa6e06.png)

Balanced accuracy score

![combo balanced acc score](https://user-images.githubusercontent.com/95251140/167316907-ee6f3340-22ae-44c2-bbfa-fcfcbbb88d98.png)

# Balanced Random Forest Classifier

![BR Forest Classifier](https://user-images.githubusercontent.com/95251140/167316982-fac2c0b3-0fe3-48f7-962a-b30109389709.png)

Balanced accuracy score

![BR forest bacc score ](https://user-images.githubusercontent.com/95251140/167316993-70626f4a-43b6-4ef4-b1eb-3fea57cac88e.png)

# Easy Ensemble AdaBoost Classifier

![AdaBoost Classifier](https://user-images.githubusercontent.com/95251140/167317017-16527759-7f98-40f6-8c70-6ca326682ab9.png)

Balanced accuracy score

![adaboost bacc score ](https://user-images.githubusercontent.com/95251140/167317025-1f493ebf-ca36-42cb-99ae-d2067ac9fd1a.png)


## Summary

The first four models show low precision when it comes to high-risk credit and the balanced accuracy scores are to low to give a good sense of credibility, therefore I would not recommend any of the first four models be used to detect credit risk. The last two models have better balanced accuracy scores, and even though the high-risk precision scores are still low there is an overall better balance between precision and sensitivity in these models with the best being the Easy Ensemble AdaBoost Classifier. To make a recommendation on just these models I would suggest using the Easy Ensemble AdaBoost Classifier model, but if there is enough time and resources available I would say to re-look at the data and test more models until the precision, sensitivity, and accuracy scores show more balanced numbers. 
