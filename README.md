BIKE SHARING PREDICTION

The objective was: Predict the total number of bicycle users on an hourly basis. https://www.kaggle.com/marklvl/bike-sharing-dataset/downloads/Bike-Sharing-Dataset.zip/1 (Overview: https://www.kaggle.com/marklvl/bike-sharing-dataset/home.

The notebook is structured the following and tries to make use of Dask Structure:

General Approach
0. Original Instructions
1. EDA
1.2 Basic satistics on numerical variables
1.3 Data Quality
1.4 Visual Analysis
1.5 Correlations
2 Feature Engineering and Selection
2.1 Feature Creation
2.2 Feature Selection
3 Machine Learning Models
3.1 Linear Reg Trial on Original Dataset hour_df
3.2 Linear Reg Trial on prepared Dataset
3.3 One hot encoding
3.4 Split Dummified Dataset
3.5 Linear Reg for Dummified dataset
3.6 Ridge Reg
3.7 Lasso Reg
3.8 Random Forest
3.9 Gradient Boosting
3.10 XGBoost
4 Model Optimization
4.1 Random Forest
4.2 Gradient Boosting
4.3 XGBoost
4.4 Stacking
5 Conclusion
5.1 Crossvalidation for final model
5.2 Best prediction
