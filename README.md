# Data-Science-Capstone-Project---Healthcare-Analytics
Post completion of Data Scientist Masters Program I have created a project on Healthcare Analytics

Business Use Case:
The data provided has details like Blood Pressure, Age, Glucose, Insulin level, etc.
The goal is to create a model which will predict if the person has diabetes or not. 

Tools used for the project:
1 - Python
2- Tableau

Steps performed in the project-
1 - Exploratory Data Analysis - Univariate Analysis by creating histograms and checking distributions, correlation analysis using heatmaps, checking balance of dataset by analyzing the target variable.
2 - Feature Selection - Used bakward elimination method since there were limited features. Used all the features first then started eliminating based on least correlation with target variable
3 - Feature Engineering - Missing value imputations, Scaling the data using Minmax Scaler
4 - Model building. Tried using different classification models like KNN, Logistic Regression, Random Forest, SVM
5 - Hyperparameter Tuning - Used RandomizedSearchCV for Hyperparameter tuning in Random Forest Classification
6 - Data Visualization - Created dashboards in Tableu to provide insights
