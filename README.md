# 🏥 Healthcare Insurance Data Analysis

This project focuses on **Exploratory Data Analysis (EDA), data cleaning, preprocessing, feature engineering, and statistical analysis** of healthcare insurance data using Python.

The objective is to understand patterns in medical insurance charges and prepare a clean, transformed dataset suitable for further machine learning applications.

## 📊 Features

* 🔍 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Duplicate Removal
* 🔢 Categorical Data Encoding
* 🏷️ Label Encoding
* 📊 One-Hot Encoding
* 🧬 Feature Engineering
* 📏 Feature Scaling
* 📈 Pearson Correlation Analysis
* 🧪 Chi-Square Statistical Analysis
* 📁 Preparation of Final Dataset for Model Training

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Jupyter Notebook

## 🔎 Analysis Performed

### Exploratory Data Analysis

Performed:

* Dataset structure and shape analysis
* Descriptive statistics
* Missing-value analysis
* Distribution analysis using histograms
* Categorical analysis using count plots
* Outlier detection using box plots
* Correlation analysis using heatmaps

### 🧹 Data Cleaning & Preprocessing

* Checked for missing values
* Removed duplicate records
* Converted categorical variables into numerical representations
* Applied label encoding to categorical variables
* Applied one-hot encoding to the `region` feature

### 🧬 Feature Engineering

Created BMI categories from the BMI feature:

* Underweight
* Healthy
* Overweight
* Obese

These categories were subsequently encoded for numerical analysis.

### 📏 Feature Scaling

Applied `StandardScaler` to selected numerical features:

* Age
* BMI
* Children

### 📈 Statistical Analysis

Performed **Pearson correlation analysis** to examine relationships between selected features and insurance charges.

A **Chi-Square test** was also performed to evaluate the relationship between categorical features and categorized insurance charges.

## 📁 Dataset

The project uses the `insurance.csv` dataset containing healthcare insurance records with features such as:

* Age
* Sex
* BMI
* Number of children
* Smoking status
* Region
* Insurance charges

## 📂 Project Structure

```text
Healthcare-Insurance-Data-Analysis/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── EDA_Data_Cleaning.ipynb
│
├── README.md
└── requirements.txt
```

## 🎯 Outcome

The project produces a cleaned and transformed dataset that can be used as a foundation for **machine learning model development and further predictive analysis**.

## 🚀 Future Scope

* Build a machine learning model to predict insurance charges
* Compare regression algorithms
* Evaluate model performance using appropriate metrics
* Develop an interactive dashboard using Power BI
* Perform deeper feature selection and model interpretation

## 👨‍💻 Author

**Akrish Chaurasia**

Data Analytics | Python | SQL | Power BI
