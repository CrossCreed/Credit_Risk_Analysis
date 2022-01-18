# Credit_Risk_Analysis

## Overview of Credit_Risk_Analysis:

### Purpose
___
> Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

> Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.

> Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

> Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

> Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### Credit_Risk_Analysis Results
___
The following screenshots will show the results obtained with the different models used to analyze for credit risk:

_(Over Sampling, Under Sampling, SMOTEENN Sampling, Balanced Random Forest Classifier & Easy Ensemble AdaBoost Classifier)._

**Over Sampling**

![image](https://user-images.githubusercontent.com/89520192/149999154-89f615f8-f731-450e-9f6a-62c92a1f8d62.png)

![image](https://user-images.githubusercontent.com/89520192/149999249-152b0ff0-61a4-417e-9add-224eb96894fb.png)

![image](https://user-images.githubusercontent.com/89520192/149999306-bf25fab3-1486-465d-85b4-8432bd635915.png)

**Under Sampling**

![image](https://user-images.githubusercontent.com/89520192/149999623-fb292887-015a-43b2-8260-244cd19fb6b7.png)

![image](https://user-images.githubusercontent.com/89520192/149999657-b4797ffe-1801-496e-b932-ff21d54fb8e9.png)

![image](https://user-images.githubusercontent.com/89520192/149999674-c58e6bfd-22e2-483b-8fea-4934223b350b.png)


**SMOTEENN Sampling**

![image](https://user-images.githubusercontent.com/89520192/149999923-70c2eba5-47c4-43e9-be48-69f90baa8039.png)

![image](https://user-images.githubusercontent.com/89520192/149999954-f6f1c74b-0f16-407f-9db6-16ff4ea11fab.png)

![image](https://user-images.githubusercontent.com/89520192/149999994-cafb1e04-eabd-4429-84c7-dc730a886b2c.png)


**Balanced Random Forest Classifier**

![image](https://user-images.githubusercontent.com/89520192/150000214-931e8248-4e7a-42c1-ace1-50dd180fe004.png)

**Easy Ensemble AdaBoost Classifier**

![image](https://user-images.githubusercontent.com/89520192/150000259-301b5869-4d40-41d1-9f16-4953a9ab0bd8.png)

### Credit_Risk_Analysis Summary
___

The Easy Ensemble AdaBoost Classifier had the highest accuracy rate at 94.28% over all other models. It also had a 7% precision rate for high_risk customers. 
Out of all the presented models, the client (bank/lending company) should feel most confident in using the Easy Ensemble AdaBoost Clasifier when selecting potential customers as this model has the highest accuracy out of all 5 models, with the highest precision as well as sensitivity.
It is nice to keep in mind however that other options/models can be explored. Although the metrics for this model are good, 7% precision rate might not be as high as a model could get with its predicion of high_risk customers. 

