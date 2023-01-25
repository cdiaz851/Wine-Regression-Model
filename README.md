# Wine-Regression-Model

For this project, my team and I were to create a regression model that would accurately predict out-of-sample wine quality values, using a dataset from Kaggle that was split into a train and test set by our professor. My team and I first created a correlation heatmap to visualize any relationship between variables. We then split our train data in order to use a k-fold as our cross validation technique. By plotting our predictor against the variables, we were able to check for any linear relationships and determine whether a transform was necessary. As we made adjustments to our model, we decided to created a variety of lasso models to compare against, some even using Leave-One-Out-Cross-Validation instead of our original 5-fold cross validation. We then tested our models against each other, looking at their RMSE, MAE, and R-squared values. This aided us to pick the model we believed would perform best in predicting out-of-sample data.

   
Link to Kaggle Dataset:
   
https://www.kaggle.com/datasets/saigeethac/red-and-white-wine-quality-datasets
