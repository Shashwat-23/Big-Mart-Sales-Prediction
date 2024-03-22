# Big-Mart-Sales-Prediction
In this project, the aim is to predict the sales of various items in Big Mart stores using machine learning techniques. Below is an overview of the steps taken in this project:

**Steps Taken**:-
 1. Preventing Data Leakage: Ensured that there was no data leakage, ensuring that information from the test set did not influence the training process.
  
 1.  Data Wrangling: Cleaned the dataset by handling missing values, removing duplicates, and converting data types as necessary.
  
 1.  Exploratory Data Analysis (EDA): Conducted exploratory data analysis to gain insights into the distribution of various features and relationships between them.
  
 1.  Feature Engineering: Created new features or modified existing ones to enhance the predictive power of the models.
  
 1. Visualizing Numerical Features Distribution and Outliers: Utilized boxplots to visualize the distribution of numerical features and identify outliers.
  
 1.  Handling Null Values: Dealt with missing values in the dataset, particularly across 'Item Weight' and 'Outlet Size' features.
  
 1.  One-Hot Encoding: Performed one-hot encoding on categorical data to convert them into a numerical format suitable for machine learning models.
  
  1. Cross-Validation with Hyperparameter Tuning: Employed cross-validation techniques along with hyperparameter tuning for various regression models including RandomForest Regressor, Gradient Boosting, and XGBoost.
  
  1. Visualizing Feature Importance: Utilized SHAP (SHapley Additive exPlanations) to visualize feature importance for each model, gaining insights into which features contribute most significantly to the predictions.

Model Performance
After rigorous evaluation, the RandomForest Regressor emerged as the top-performing model with the following metrics:

  1.R-squared (R2) Score: 0.603
  
  2.Root Mean Squared Error (RMSE): 1054.45
  
  3.Standard Deviation: 1054.074

A small difference between RMSE and standard deviation indicates that the model's performance is reliable and stable across different data points.The model is likely generalizing well to unseen data.


**Created** a **Power BI** dashboard showcasing sales data analysis. The dashboard provides insights into various aspects of sales performance, including outlet stores, total sales, number of unique items, average sales, highest item outlet sales, sales across different city tiers, item sales by category, preferred MRP ranges, and the effect of outlet size on item sales.
