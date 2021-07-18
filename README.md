# Credit_Risk_Analysis

## Overview

By training and evaluating models via Python, the goal of this analysis was to help predict credit risk. Specifcally we used imbalanced-learn and scikit-learn librariries to do so. With the given dataset from LendingClub, oversampling the data by using RandomOverSampler and SMOTE algorithms and undersampling by using ClusterCentroids algorithm will allow for consistent training and balance of both minority and majority data. Two additional machine learning models were also used to minimize bias.

## Results of using each model

1. Random Over Sampler
  - The balance accuracy test had a score of 65 percent
  - Precision for predicting high risk is 1 percent and low risk is 100 percent
  - Recall score for both high and low risk is 65 percent

![Screen Shot 2021-07-18 at 3 50 40 PM](https://user-images.githubusercontent.com/80358062/126080365-af63997d-522f-470b-bbb8-3b7e2ac59096.png)

![Screen Shot 2021-07-18 at 3 51 56 PM](https://user-images.githubusercontent.com/80358062/126080386-05300fa8-e178-4fce-ba4e-177b16c8ed1d.png)

2. SMOTE
  - The balance accuracy test had a score of 60.5 percent
  - Precision for predicting high risk is 1 percent and low risk is 100 percent
  - Recall score for both high risk was 56 percent and low risk is 65 percent
  
![Screen Shot 2021-07-18 at 3 52 41 PM](https://user-images.githubusercontent.com/80358062/126080400-d1d13c59-f0c2-4a1d-a801-cf034baa536a.png)

![Screen Shot 2021-07-18 at 3 53 07 PM](https://user-images.githubusercontent.com/80358062/126080411-5a408c50-fa12-4ab4-ad4b-99099b1729c8.png)

3. Random Under Sampler
  - The balance accuracy test had a score of 60 percent
  - Precision for predicting high risk is 1 percent and low risk is 100 percent
  - Recall score for both high risk was 62 percent and low risk is 59 percent

![Screen Shot 2021-07-18 at 3 53 37 PM](https://user-images.githubusercontent.com/80358062/126080424-221a45a9-6ba5-40df-8d39-18449f779e64.png)

![Screen Shot 2021-07-18 at 3 53 56 PM](https://user-images.githubusercontent.com/80358062/126080433-5e306d90-fd76-492f-8fdf-7f267a25a663.png)

4. SMOTEENN
  - The balance accuracy test had a score of 65 percent
  - Precision for predicting high risk is 1 percent and low risk is 100 percent
  - Recall score for both high risk was 73 percent and low risk is 57 percent

![Screen Shot 2021-07-18 at 3 54 28 PM](https://user-images.githubusercontent.com/80358062/126080450-16e1b9e6-acdf-487c-8be9-45bb561c63b6.png)

![Screen Shot 2021-07-18 at 3 54 44 PM](https://user-images.githubusercontent.com/80358062/126080458-fdb0b7b0-930e-4137-aeda-9a12d299a6bd.png)

5. Balanced Random Forest Classifier
  - The balance accuracy test had a score of 78 percent
  - Precision for predicting high risk is 4 percent and low risk is 100 percent
  - Recall score for both high risk was 65 percent and low risk is 91 percent

![Screen Shot 2021-07-18 at 3 55 30 PM](https://user-images.githubusercontent.com/80358062/126080477-db44a128-03ce-4e55-bed7-884f6564aa6a.png)

![Screen Shot 2021-07-18 at 3 55 49 PM](https://user-images.githubusercontent.com/80358062/126080488-9fb82199-ac0a-43f9-8085-ac42600f7c38.png)

6. Easy Ensemble Classifier
  - The balance accuracy test had a score of 91 percent
  - Precision for predicting high risk is 9 percent and low risk is 100 percent
  - Recall score for both high risk was 87 percent and low risk is 95 percent

![Screen Shot 2021-07-18 at 3 56 17 PM](https://user-images.githubusercontent.com/80358062/126080497-a85a1581-755a-4027-98fe-47e42c853e9e.png)

![Screen Shot 2021-07-18 at 3 56 29 PM](https://user-images.githubusercontent.com/80358062/126080508-da1346de-7701-4520-ae64-13bc3de8c4ed.png)

## Summary

Using both oversampling and undersampling we were able to determine which model can best predict high risk loans. Precision in determining this was very weak using the first four models but the Ensemble models showed higher precision and had an overall better balance between precision and recall. Specifically the Easy Ensemble Classifier model had a good balance berween precision and risk and a high accuracy score.


