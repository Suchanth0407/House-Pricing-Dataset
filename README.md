# House-Pricing-Dataset

# 🏡 House Pricing Dataset Analysis using Python and EDA

This project explores the **Ames Housing Dataset** using **Python** and **Exploratory Data Analysis (EDA)** techniques. The goal is to identify key drivers of house prices and prepare the dataset for machine learning.

---

## 📂 Dataset

We use the [Ames Housing Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) from Kaggle, which contains comprehensive information on residential home sales in Ames, Iowa.

📌 Dataset link:  
**[👉 Click to access the dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)**

> **Note:** A free Kaggle account is required to download the dataset.

---

## 🎯 Objectives

- Clean and preprocess raw housing data
- Perform univariate and multivariate analysis
- Identify correlations and trends
- Visualize key insights using Python libraries
- Prepare dataset for regression modeling

---

## 🛠️ Tools & Libraries

- **Python 3.8+**
- **Pandas**, **NumPy** – Data cleaning & manipulation
- **Seaborn**, **Matplotlib** – Visualizations
- **Jupyter Notebook**
- (Optional) **Scikit-learn** – for preprocessing and modeling

---

## 📊 EDA Process Overview

### 1️⃣ Data Loading & Inspection
- Overview of features and target variable
- Checked for nulls and incorrect types

### 2️⃣ Handling Missing Values
- Imputed missing values using domain logic
- Dropped irrelevant or high-null columns

### 3️⃣ Univariate Analysis
- Distribution of `SalePrice`, `GrLivArea`, `LotArea`, etc.
- Count plots for `Neighborhood`, `HouseStyle`, etc.

### 4️⃣ Bivariate & Multivariate Analysis
- Correlation heatmap
- Scatter plots between `SalePrice` and numerical features
- Groupby stats for categorical features

### 5️⃣ Outlier Detection
- Boxplots and IQR-based filtering
- Visual inspection of `GrLivArea`, `SalePrice`

### 6️⃣ Feature Engineering
- New features like `TotalBathrooms`, `HouseAge`
- Log transformation of skewed columns

---

## 📈 Key Insights

- High-quality construction (`OverallQual`) greatly influences price.
- `GrLivArea` and `GarageCars` are strong positive predictors.
- Location (`Neighborhood`) is a significant factor.
- Some features require normalization before modeling.

---

