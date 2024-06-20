Goal :
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

Steps :
1. Read Training CSV file
2. Check missing values
3. Decide Strategy for Con, Cat features , Cat most_frequent, constant
4. EDA (Univariate, Bivarite) 
5. Sklearn Pipeline  1. Feature selection (Ordinal Encode) 2. Final Pipeline(OneHotEncoder)
6. Feature selection (Forward, Backward) - LinearRegression
7. Train Test Split
8. Final Model Building (Rigde/Lasso) 
9. Apply Ridge Lasso with GridSearchCV
10. Model Predction for train, test split
11. Evaluate model with MSE, RMSE, MAE, R2 
12. Predict the sample_set.csv 
