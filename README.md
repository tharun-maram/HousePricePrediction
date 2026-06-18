# House Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze various house features such as area, number of bedrooms, bathrooms, stories, parking availability, and amenities to estimate the selling price of a property.

The project was completed as part of an internship assignment and follows the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, visualization, and business insights generation.

---

## Dataset

**Dataset Name:** Housing Prices Dataset

**Source:** Kaggle

The dataset contains 545 housing records with 13 features describing different characteristics of residential properties.

### Features Included

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

### Target Variable

* **Price** (House Selling Price)

---

## Project Workflow

### 1. Data Loading and Exploration

* Loaded dataset using Pandas
* Examined dataset structure and dimensions
* Identified features and target variable
* Checked data types and missing values

### 2. Data Cleaning and Preprocessing

* Verified absence of missing values
* Checked and removed duplicate records
* Converted categorical features into numerical format using One-Hot Encoding
* Prepared data for machine learning models

### 3. Model Building

Two regression models were implemented:

#### Linear Regression

A statistical model used to understand the relationship between house features and price.

#### Random Forest Regressor

An ensemble learning model that combines multiple decision trees for prediction.

---

## Model Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

#### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

#### Random Forest Regressor

* MAE: 1,021,546
* RMSE: 1,400,565
* R² Score: 0.612

### Best Performing Model

Linear Regression performed better than Random Forest on this dataset, achieving lower prediction error and a higher R² score.

---

## Data Visualizations

The following visualizations were created:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted House Price Scatter Plot

These charts help understand data distribution, feature relationships, and model performance.

---

## Key Findings

* House area is one of the strongest factors influencing property price.
* Additional amenities such as air conditioning, parking, and preferred location contribute significantly to higher prices.
* The dataset was clean with no missing values or duplicate records.
* Linear Regression provided more accurate predictions than Random Forest for this dataset.

---

## Business Recommendation

Real estate companies can use predictive analytics models to estimate property values more accurately. Special attention should be given to property size, location-related features, and amenities when determining market prices and investment opportunities.

---

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

---

## Project Structure

HousePricePrediction/

├── analysis.ipynb

├── Housing.csv

├── Summary.docx

├── charts/

│ ├── chart1.png

│ ├── chart2.png

│ └── chart3.png

└── README.md


