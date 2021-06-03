# Wine-Quality-Prediction

In this project, I work on [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from UCI Machine Learning Repository. This notebook consists of my approach for finding the best way to predict the Wine Quality with this dataset.

For this project, I've taken inspiration from work of people on [Wine Quality Kaggle Dataset](https://www.kaggle.com/rajyellow46/wine-quality/code). Please note that the dataset on Kaggle is slightly different from UCI Respository. I hope anyone looking at this finds some value out of my work. :)
<br>

Citation:<br>
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

### Overview of Project:

- __Preparing Data:__ We read the dataset, add column for wine type, and scale it.
- __EDA:__ We do basic checks for null values, check details of all attributes, and do basic visualisations to get insights from the dataset.
- __Solving Class Imbalance:__ We try to solve Class Imabalance issue in dataset using class weights, oversampling, and aggregation of classes.
- __Spot-Checking Algorithms:__ We check which algorithm would be best for our dataset by doing cross validation with various algorithms for classification. For this, we use a [Spot-Check framework](https://machinelearningmastery.com/spot-check-machine-learning-algorithms-in-python/).
- __Hyperparameter Tuning:__ From the results of Spot-Checking, we pick three best. Also comparing them with Deep Learning model and go ahead with best performing model. We do hyperparameter tuning for best model and analyse results.
- __Conclusion:__ We conclude which model(s) would be useful and why. Also mentioning further work to be done.
