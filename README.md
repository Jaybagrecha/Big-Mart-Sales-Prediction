# Big Mart Sales Prediction
Solution of the Bigmart Sales Prediction problem by Analytics Vidhya
### Problem Statement 		  
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

### What I did:
1. Replaced the Nans and zero values, identified outliers, feature selection and normalization - for both train and test data.
2. Visualised the data, studied the correlation amongst the data and chose the required features.
3. Built the models: I created a single model function to which I passed various different models such as Linear Regression, Decision Trees and Random Forests. I will soon be adding tree boosting to it as well.
4. Calculated the Root Mean Squared Error (RMSE), predicted the sales, cross validated the scores.
5. Classified the train data and imported the results for respective machine learning models to separate csv files (which have been attached above). The Decision Tree algorithm proved to be a clear winner with the lowest RMSE value.
