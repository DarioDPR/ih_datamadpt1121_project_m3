# ih_datamadpt1121_project_m3
![price11](https://user-images.githubusercontent.com/91491555/162503288-ea46b41c-6e56-4eec-95ee-478851a4337d.jpg)

## Kaggle Competition
Details: https://www.kaggle.com/competitions/dataptmad1121/overview
The  goal of the competition  is to predict the price of diamonds based on their features

### Workflow
Language: Python
Libraries : [numpy] (https://numpy.org/) ,pandas,sklearn

1. A previous study of diamonds features and their influence in price has been done in Module 2 Project https://github.com/DarioDPR/ih_datamadpt1121_project_m2/tree/ih_datamadpt1121_project_m2
2. First we drop index_id and city columns from train dataset as they are not relevant values
3. Next we have to identify numeric and categorical values as we have to turn categorical into 0-1 coded values to be identified by ML models. We also define the target which is the price
5. Scaling of numerical values is next step, we apply StandardScaler
6. With the numerical scaled data and the "dummies" caterigocal values we create one dataframe which is our final train set
7. We apply train-test-split which allows us to split the dataset into two blocks: model training and validation
8. Model Training: RandomForestRegressor
9. Then we make 20% prediction with relative mean squared error that gives as a 'hint' of the final result
10. We apply the same changes to test dataset and we get the predictiond dataet to be submitted

### Conclusions
My score applied to half of the prices to be predicted is 651.07449 
