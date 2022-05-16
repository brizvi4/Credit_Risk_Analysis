# Credit Risk Analysis

## Overview

In this module, I helped Jill in analysing  credit card credit dataset from LendingClub in order to find out good loans and bad loans. For this analysis, I used machine learning models to predict credist risk. I used a total of six different models and checked which model gave the best result. The machine learning models I used are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier. I calculated balanced accuracy scores and the precision and recall scores of all six machine learning models to reach an informed decision. 

## Results

- Random Oversampling:

<img width="493" alt="Pic1" src="https://user-images.githubusercontent.com/95254809/168647572-ece30d09-3a5f-438d-967a-a05538c1348f.PNG">

The balanced accuracy score for this model is 0.6573.The model is not very precise when it comes to predicting high risk lows. Recall for high risk is 0.71 which is also not very good. 

- SMOTE Oversampling:

<img width="496" alt="Pic2" src="https://user-images.githubusercontent.com/95254809/168647726-1e13f1e0-bec9-4fa6-b934-7742db9d8d56.PNG">

The balanced accuracy score for this model is 0.6622 which is very similar to the previous model. Precision and recall values are also similar to the previous model.

- Undersampling:

<img width="500" alt="Pic3" src="https://user-images.githubusercontent.com/95254809/168647953-0bef8727-d983-48b3-b928-0f97b9569e2c.PNG">

The balanced accuracy score for this model is 0.5645897 which is lower than the previous models. Precision and recall values are  similar to the previous models.

- SMOTEENN - Combination (Over and Under) Sampling:

<img width="504" alt="Pic4" src="https://user-images.githubusercontent.com/95254809/168648257-3233d7f9-49c8-40de-b48e-b731b8c562ff.PNG">

The balanced accuracy score for this model is 0.64471. Precision and recall values are  similar to the previous models.

- Balanced Random Forest Classifier

<img width="507" alt="Pic5" src="https://user-images.githubusercontent.com/95254809/168648426-3cfc6eaa-c1b6-4d88-989a-d0cfef187753.PNG">

The balanced accuracy score for this model is 0.7885 which is considerably higher than the previous models we have seen. Precision is just a tiny but higher than the previous models but it is still very low with a value of 0.03. Recall value is similar to the previous models. 

- Easy Ensemble AdaBoost Classifier:

<img width="512" alt="Pic6" src="https://user-images.githubusercontent.com/95254809/168649618-14f726d4-8c9f-44ef-bc4a-379493ca3b4f.PNG"> 

The balanced accuracy score for this model is 0.93166 which is the highest amongst all the models. Precision and recall values of this model are also the highest.

## Summary

From the results, we can see that the highest balanced accuracy score is for Easy Ensemble AdaBoost Classifier. 




