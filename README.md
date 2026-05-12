# real-estate-price-prediction
Machine learning project for real estate price prediction using EDA, feature engineering, and regression model evaluation in Python, using a raw real life dataset published by Divar.ir

Overview:

This project explores machine learning approaches for predicting real estate prices based on property characteristics, location-related features, and structured advertisement data.

The project includes:

exploratory data analysis (EDA),
data preprocessing,
feature engineering,
regression model experimentation,
and model evaluation for business-oriented price estimation.

The goal was to better understand how machine learning workflows can support real-world pricing and decision-making problems in the real estate domain.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Jupyter Notebook / Google Colab
Workflow
1. Business Understanding
Defined the pricing prediction problem
Identified key business and market-related variables
2. Exploratory Data Analysis (EDA)
Distribution analysis
Correlation analysis
Bivariate analysis
Geospatial exploration
Outlier detection
3. Data Cleaning & Preprocessing
Handling missing values
Data normalization and transformation
Feature preparation
4. Feature Engineering
Property-related engineered variables
Pricing-related transformations
Location feature preparation
5. Model Training & Evaluation

Experimented with multiple regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
XGBoost Regressor

Models were compared using performance evaluation metrics to determine the most effective approach.

Key Learning Outcomes
Building end-to-end machine learning workflows
Understanding feature engineering impact on prediction performance
Comparing regression algorithms for structured business data
Applying analytical thinking to real-world pricing problems
Structuring ML experimentation in a reproducible workflow
Future Improvements

Potential future improvements include:

advanced geospatial feature engineering,
hyperparameter optimization,
deployment as an interactive web application,
and integration with real-time market data sources.

# Project Structure

```bash
├── real_estate_price_prediction.ipynb
├── README.md
├── requirements.txt

## Author
Homa Rad

## Requirements

pandas  
numpy  
matplotlib  
scikit-learn  
xgboost  
