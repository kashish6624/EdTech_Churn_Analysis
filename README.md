# EdTech Churn Analysis

## Project Overview

This project analyzes student data from an EdTech platform to understand what factors influence student performance and potential churn.

In addition to Exploratory Data Analysis (EDA), this project builds Machine Learning models to predict student performance levels and identify at-risk students.

---

## Dataset Used

* You can find the dataset in the repository itself.
* The dataset contains student-related information such as:

  * Demographics (gender, nationality, etc.)
  * Academic details (grade level, subjects)
  * Behavioral data (raised hands, visited resources, etc.)
  * Student performance class (target variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Steps Performed

### 1. Data Loading & Inspection

* Loaded dataset using Pandas
* Checked:

  * Shape of dataset
  * Data types
  * Missing values
  * Basic statistics

### 2. Data Cleaning

* Verified absence of null values
* Ensured correct data formats
* Prepared dataset for analysis

### 3. Exploratory Data Analysis (EDA)

* Univariate Analysis (distribution of individual features)
* Bivariate Analysis (relationship with target variable)
* Visualizations:

  * Count plots
  * Histograms
  * Box plots
  * Correlation insights

### 4. Machine Learning Models

The following models were implemented and evaluated:
* Logistic Regression
* Decision Tree
* Random Forest

### 5. Model Evaluation

* Accuracy comparison
* Confusion matrix
* Performance analysis

---

## Key Insights

* Student engagement is the strongest predictor of performance
* Attendance and participation directly impact outcomes
* Parental involvement significantly improves performance
* ML models can effectively classify students into performance categories

---

## Results

* Best model: Random Forest
* Accuracy achieved: 97.9%
