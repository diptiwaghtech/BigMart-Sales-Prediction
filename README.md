# BigMart Sales Prediction

## Project Overview
This project focuses on predicting product sales for BigMart outlets using Machine Learning Regression techniques. The objective is to analyze various product and outlet characteristics and build predictive models that estimate the sales of products across different stores.

## Problem Statement
Retail businesses need accurate sales forecasting to improve inventory management, marketing strategies, and business planning. This project uses historical BigMart sales data to predict future sales performance based on product and outlet attributes.

## Dataset Features
The dataset contains information related to:

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type
- Item Outlet Sales (Target Variable)

## Project Workflow

### 1. Data Collection
- Loaded BigMart sales dataset using Pandas.

### 2. Data Preprocessing
- Handled missing values.
- Cleaned categorical features.
- Performed feature engineering where required.
- Converted categorical variables into numerical representations.

### 3. Exploratory Data Analysis (EDA)
- Examined feature distributions.
- Identified relationships between variables.
- Visualized sales trends using Matplotlib and Seaborn.

### 4. Feature Selection
- Analyzed feature importance.
- Selected relevant features for model training.

### 5. Model Building
Multiple regression models were trained and evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor
- K-Nearest Neighbors Regressor
- Support Vector Regressor (SVR)

### 6. Model Evaluation
Models were evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
BigMart-Sales-Prediction/
│
├── BigMart Sales Prediction.ipynb
├── Dataset18-Bigmart_sales.csv
├── README.md
```

## Results
Different machine learning regression algorithms were compared to identify the model that provides the best sales prediction performance. Feature importance analysis was also performed to understand the factors influencing product sales.

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Advanced ensemble methods
- Deployment using Flask/Streamlit
- Real-time sales prediction dashboard
