# Loan Approval Prediction - Data Analysis & Preprocessing

## Overview

I aimed on building a strong data analysis foundation for **loan approval prediction** by exploring and preprocessing a dataset of loan applicants.

The objective is to identify the key factors that influence **creditworthiness**, helping financial institutions make informed lending decisions while minimizing financial risk.

---

## Project Workflow

### 1. Data Loading & Inspection

Without gatekeeping anything, I will explain whole workflow so you can do this as well.First  The dataset was imported and examined to understand its structure and overall quality.

**Tasks performed:**
- Loaded the dataset
- Checked dataset shape
- Inspected data types
- Identified missing values
- Evaluated overall data quality

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the data, identify outliers, and discover relationships between variables.

#### Histograms
Used to analyze the distribution of:
- Age
- Income
- Credit Score

**Purpose**
- Understand data distribution
- Detect skewness
- Identify common value ranges

#### Count Plots
Visualized categorical variables such as:
- Gender
- Education Level
- Loan Status

**Purpose**
- Analyze applicant demographics
- Observe loan approval distribution

#### Box Plots
Created for:
- Age
- Income
- Credit Score

**Purpose**
- Detect outliers in numerical features

#### Correlation Heatmap

**Purpose**
- Measure relationships between numerical variables
- Identify highly correlated features (e.g., Income and Credit Score)

---

### 3. Data Cleaning & Preprocessing

The raw dataset was transformed into a machine learning-ready format.

#### Cleaning Steps

- Removed duplicate records
- Converted binary categorical variables into numerical values (0/1)
  - Gender
  - Marital Status
  - Loan Status
- Applied **One-Hot Encoding** to:
  - Education Level
  - Occupation

---

### 4. Feature Engineering & Selection

Feature engineering techniques were applied to improve future model performance and identify the most important predictors.

#### Feature Scaling
Used **StandardScaler** to normalize:
- Age
- Income

**Purpose**
- Prevent large-scale features from dominating machine learning algorithms.

#### Pearson Correlation

Used to measure the linear relationship between numerical features and **Credit Score**.

**Purpose**
- Identify strong numerical predictors.

#### Chi-Square Test

Evaluated associations between categorical variables and a binned Credit Score.

**Purpose**
- Select statistically significant categorical features for modeling.

---

## Project Outcome

This project establishes a complete preprocessing pipeline by:

- Cleaning raw data
- Handling categorical variables
- Scaling numerical features
- Exploring feature relationships
- Selecting statistically significant predictors

These steps provide a solid foundation for building accurate, interpretable, and reliable machine learning models for **loan approval prediction** and **credit risk assessment**.

---

## Tech Stack

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy

---

## Dataset

**Loan Prediction Dataset**

🔗 https://www.kaggle.com/datasets/mosaadhendam/loan-prediction-dataset

---

## Credits

This project was developed using Python data science libraries in **Google Colab** for data analysis, preprocessing, and feature engineering.
