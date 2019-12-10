# Kaggle Data Science Contest: Predicting Future Sales
This repo contains the code used for entering my first Kaggle Contest. An academic journal draft is also included in this repo.
Link to Kaggle:https://www.kaggle.com/c/competitive-data-science-predict-future-sales
I won a best rank of 1007 on the Kaggle Leaderboard, with an error of 0.91777.

## How the competition works
Contestants submit a .csv file onto Kaggle, and the system assesses the result based on the RMSE(Root mean squared error). The lower the RMSE, the better the code and used model, therefore, the higher the ranking.

## How I progressed in the competition
The first and most important thing to look at in data science is the data. The image below is part of the data graphed out in a Jupyter Notebook.

![Items Sales Per Month](https://github.com/JustRodneyLee/Kaggle-Predict-Future-Sales/blob/master/ItemSalesPerMonth.png?raw=true)

It can be observed that the sales of each item doesn't change much throughout the year, except for January (possibly because of the coming  New Year). Therefore, a basic model can be created. Simply by assuming that the sales don't change gives me a "worst" error value, a value that serves as the baseline for my future predictions.

Another important thing to do engineering on is features - certain data columns that might affect the predicted result. After fitting the selected data columns into a new model, Jupyter Notebook prodcues an image that represents a graph of the importance values of the selected features.

![Feature Importance](https://github.com/JustRodneyLee/Kaggle-Predict-Future-Sales/blob/master/FeatureImportance.png?raw=true)

By removing and adding certain data columns for the model to train on, I can make several different predictions, from which I selected the prediction with the smallest RMSE and uploaded it onto Kaggle to be tested.

For more details, please read the academic journal included in the repository.
