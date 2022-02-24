# Credit_Risk_Analysis
## Overview
Oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results
### Naive Random Oversampling
* The balanced accuracy score was 63.3%
* The high risk precision score was 1%
* The high risk recall score was 65%

![Screen Shot 2022-02-24 at 1 35 40 PM](https://user-images.githubusercontent.com/38327290/155586254-185acf16-54c8-4a59-bd9b-001070ef3a8e.png)

### SMOTE Oversampling
* The balanced accuracy score was 65.5%
* The high risk precision score was 1%
* The high risk recall score was 61%

![Screen Shot 2022-02-24 at 1 38 44 PM](https://user-images.githubusercontent.com/38327290/155586716-699ef7fe-3949-410b-aa09-75d58798343f.png)

### Undersampling 
* The balanced accuracy score was 54.4%
* The high risk precision score was 1%
* The high risk recall score was 69%

![Screen Shot 2022-02-24 at 1 44 10 PM](https://user-images.githubusercontent.com/38327290/155587448-d6af1fe5-c712-4724-bf17-2f88e7126ae7.png)


### Combination
* The balanced accuracy score was 64.8%
* The high risk precision score was 1%
* The high risk recall score was 72%

![Screen Shot 2022-02-24 at 1 44 51 PM](https://user-images.githubusercontent.com/38327290/155587531-4561de74-2167-425f-b4ba-af175b380de9.png)


### Balanced Random Forest Classifier
* The balanced accuracy score was 75.6%
* The high risk precision score was 3%
* The high risk recall score was 62%

![Screen Shot 2022-02-24 at 1 45 28 PM](https://user-images.githubusercontent.com/38327290/155587601-53024a37-ce8c-4148-b217-163abb169016.png)


### Easy Ensemble AdaBoost Classifier 
* The balanced accuracy score was 75.6%
* The high risk precision score was 3%
* The high risk recall score was 62%

![Screen Shot 2022-02-24 at 1 46 17 PM](https://user-images.githubusercontent.com/38327290/155587701-b880e0fc-fe75-4275-91dd-acfd706701af.png)

## Summary
The random forest and ensemble classifier had the highest precision scores, but the combination had the highest recall score, so I recommend one of those.
