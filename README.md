# Real Estate Price Prediction Project

## Overview
This project aims to develop a predictive model to estimate the median house value based on various features such as location, housing characteristics, and economic indicators. The project involves exploratory data analysis (EDA), data preprocessing, model building using Random Forest Regressor, and deployment of the model for a Streamlit application.

## Project Structure
1. Exploratory Data Analysis (EDA):
  - Identified missing values, outliers, and correlations.
  - Explored the distribution of features and their relationship with the target variable.

2. Data Preprocessing:
  - Checked for duplicates and missing values.
  - Handled outliers using the interquartile range (IQR) method.
  - Engineered new features like income per capita and rooms per household.
  - Encoded categorical features like 'ocean_proximity'.
  - Selected relevant features using Recursive Feature Elimination with Cross-Validation (RFECV).
    
3. Model Building:
  - Constructed a pipeline with feature scaling, RFECV, and Random Forest Regressor.
  - Utilized GridSearchCV to tune hyperparameters of the Random Forest model.
  - Evaluated model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), R-squared (R2), and Mean Squared Logarithmic Error (MSLE).
    
4. Model Deployment:
  - Deployed the trained Random Forest Regressor model using Joblib.
  - Prepared for integration into a Streamlit application for real-time predictions.

## Files in Repository
MachineLearning_NjinjuZilefacFogap.ipynb: Jupyter Notebook containing the main project code.
RF_model.joblib: Serialized Random Forest Regressor model.
README.md: This file summarizing the project.

## Instructions for Running the Code
1. Ensure you have all necessary dependencies installed (joblib, numpy, pandas, scikit-learn, etc.).
2. Run the code in main.ipynb in a Jupyter Notebook environment or any Python IDE.
3. Follow the code comments and execute each cell sequentially.
4. After training and evaluating the model, deploy the trained model for future predictions.

## Conclusion

The project successfully developed a robust predictive model for estimating median house values. By leveraging Random Forest Regressor with feature selection and hyperparameter tuning, the model demonstrated strong predictive capabilities. The R-squared value of around 0.81 indicates that approximately 81% of the variance in median house value was explained by the model, making it suitable for real-world applications and unseen data.

## Contributors
Njinju ZIlefac Fogap
