# AI-ML-INTERNSHIP-DAY-3
# Task 3: Linear Regression – Housing Price Prediction 🏠

This project focuses on applying *Simple and Multiple Linear Regression* techniques to predict house prices. The dataset contains various features such as number of bedrooms, furnishing status, area, and more.

---

## 🎯 Objective

- Implement and understand *Linear Regression* using Scikit-learn.
- Perform data preprocessing, train-test split, model training, and evaluation.
- Analyze model performance using error metrics.

---

## 🧰 Tools and Libraries

This project uses the following Python libraries:

- *Pandas* – data manipulation and analysis
- *NumPy* – numerical operations
- *Matplotlib & Seaborn* – data visualization
- *Scikit-learn* – machine learning algorithms and metrics
- *KaggleHub* – to load dataset directly from Kaggle

---

## 📂 Dataset

- *Title*: Housing Price Prediction Dataset
- *Source*: Kaggle via [KaggleHub](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- *Format*: CSV file
- *Features include*:
  - Area (in square feet)
  - Number of bedrooms
  - Number of bathrooms
  - Furnishing status
  - Number of stories
  - Parking availability
  - Price (Target variable)

---

## 📊 Key Steps and Analysis

### 📌 1. Data Loading
- Dataset is imported from Kaggle using KaggleHub.
- CSV file is read using Pandas.

### 📌 2. Exploratory Data Analysis (EDA)
- Use of .info(), .describe(), .head() to inspect dataset.
- Distribution plots, heatmaps, and scatter plots to explore feature relationships.

### 📌 3. Data Preprocessing
- Categorical features (like 'furnishing status') are encoded using OneHotEncoder.
- Feature selection and target identification.

### 📌 4. Model Building
- Train-Test split (80/20)
- Linear Regression model training using LinearRegression() from Scikit-learn.

### 📌 5. Model Evaluation
- Metrics used:
  - *Mean Squared Error (MSE)*
  - *R² Score (coefficient of determination)*
