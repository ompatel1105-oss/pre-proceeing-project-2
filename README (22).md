# 🏥 Patient Health Data Preprocessing Project

## 📌 Project Overview

This project focuses on **data preprocessing and cleaning** of a patient
health dataset.\
The dataset contains **550 records** with multiple real-world issues
such as missing values and outliers.

------------------------------------------------------------------------

## 📊 Dataset Features

-   Patient ID\
-   Age\
-   Gender\
-   Region\
-   BMI (Body Mass Index)\
-   Blood Pressure\
-   Cholesterol\
-   Glucose\
-   Disease Risk

------------------------------------------------------------------------

## ⚠️ Problems Identified

-   Missing values in multiple columns\
-   Presence of extreme outliers\
-   Categorical data inconsistencies\
-   Data not ready for ML models

------------------------------------------------------------------------

## 🛠️ Steps Performed

### 1. Data Generation

-   Synthetic dataset created using NumPy\
-   Realistic distributions applied\
-   Missing values and outliers added intentionally

### 2. Missing Value Handling

-   **BMI** → Mean & Median Imputation\
-   **Age, Cholesterol, Glucose** → KNN Imputer\
-   **Advanced Method** → MICE (Iterative Imputer)\
-   **Categorical (Gender, Region)** → Most frequent value

### 3. Outlier Handling

-   Detected using statistical methods\
-   Applied **Winsorization** to cap extreme values

### 4. Data Visualization

-   Histograms (Before vs After Cleaning)\
-   Bar charts (Missing values)\
-   Pie charts (Categorical distribution)\
-   Correlation heatmap

------------------------------------------------------------------------

## 📈 Key Results

-   All missing values handled successfully\
-   Outliers reduced without data loss\
-   Clean and structured dataset\
-   Ready for Machine Learning

------------------------------------------------------------------------

## 🔍 Insights

-   Weak correlation between most features\
-   Disease risk not strongly dependent on single variable\
-   Balanced dataset after preprocessing

------------------------------------------------------------------------

## 🚀 Tools & Libraries Used

-   Python\
-   NumPy\
-   Pandas\
-   Matplotlib\
-   Seaborn\
-   Scikit-learn

------------------------------------------------------------------------

## 💡 Why This Project is Important

-   Demonstrates complete data preprocessing pipeline\
-   Covers both basic and advanced techniques\
-   Simulates real-world messy data\
-   Strong foundation for ML projects

------------------------------------------------------------------------

## ✅ Conclusion

This project shows how raw healthcare data can be transformed into a
**clean, reliable, and analysis-ready dataset** using modern data
preprocessing techniques.

------------------------------------------------------------------------

## 📂 Future Work

-   Apply Machine Learning models\
-   Perform feature engineering\
-   Improve prediction accuracy

------------------------------------------------------------------------

⭐ If you like this project, feel free to use or improve it!
