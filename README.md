# Big_Mart_Sales_Predicion_ML
This project builds a Big Mart Sales Prediction system using Machine Learning with Python. It includes data cleaning, handling missing values, exploratory data analysis, label encoding, and training an XGBoost Regressor to predict outlet sales. Model performance is evaluated using R² score.

# Big Mart Sales Prediction using Machine Learning

## Project Overview
This project aims to predict Item Outlet Sales for Big Mart stores using Machine Learning. It covers data preprocessing, exploratory data analysis, feature engineering, and regression model development to estimate sales accurately.

## Dataset
The Big Mart Sales dataset contains information related to products and outlets, including both numerical and categorical features used for sales prediction.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Data Preprocessing
- Handled missing values:
  - Item_Weight filled using mean
  - Outlet_Size filled using mode based on Outlet_Type
- Standardized categorical variables
- Applied Label Encoding to categorical features
- Ensured data consistency and cleanliness

## Exploratory Data Analysis
- Visualized distributions of numerical features
- Analyzed categorical feature frequencies
- Identified patterns and relationships influencing sales

## Model Building
- Algorithm: XGBoost Regressor
- Split data into training and testing sets (80/20)
- Trained the model on processed features
- Evaluated performance using R² score

## Results
The model achieved strong R² scores on both training and test datasets, indicating good predictive performance and generalization.

## How to Run
1. Clone the repository
2. Install required dependencies
3. Run the notebook or Python script
4. Train and evaluate the model

## Conclusion
This project demonstrates an end-to-end machine learning workflow for regression tasks, including data preprocessing, visualization, model training, and evaluation.

## Author
Aashish Narayan
