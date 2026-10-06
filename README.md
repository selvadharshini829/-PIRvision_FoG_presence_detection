PIR Vision Office – Machine Learning Classification 📌

Project Overview

This project focuses on building a Machine Learning classification model using the **PIR Vision Office dataset** with Python.

The main objective of the project is to analyze office-related data, perform data preprocessing and feature selection, handle class imbalance, train multiple Machine Learning classification models, and evaluate their performance using suitable evaluation metrics.

The project implements classification algorithms such as **Logistic Regression, Decision Tree, Random Forest, AdaBoost, and Gradient Boosting** to predict the target **Label**.

---

🎯 Objectives

* To understand and analyze the PIR Vision Office dataset.
* To examine the structure and characteristics of the dataset.
* To identify the target variable and input features.
* To perform data cleaning and preprocessing.
* To identify and handle missing values and duplicate records.
* To analyze correlations between numerical features.
* To detect and handle outliers using the IQR method.
* To encode the target variable using Label Encoding.
* To handle class imbalance using SMOTE.
* To select the most important features using SelectKBest.
* To transform and scale the selected features.
* To train multiple Machine Learning classification algorithms.
* To evaluate and compare model performance using Accuracy, Precision, Recall, and F1-Score.

---

 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

📂 Project Workflow

1. Data Collection

The PIR Vision Office dataset was loaded into the Python environment using Pandas.

The dataset was imported from:

`pirvision_office_dataset1.csv`

The data was converted into a Pandas DataFrame for further analysis.

---

2. Data Understanding and Preprocessing

The dataset was examined to understand its structure and characteristics.

The preprocessing and data analysis steps included:

* Loading the dataset
* Viewing the first and last records
* Checking dataset information
* Checking the number of rows and columns
* Identifying column names
* Generating descriptive statistics
* Checking missing values
* Checking duplicate records
* Identifying the target variable
* Analyzing target class distribution

The target variable identified in the project is:

**Label**

The columns **Date** and **Time** were excluded from the Machine Learning input features.

---

3. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the relationships and distribution of the dataset.

The following techniques were used:

* Descriptive statistics
* Correlation analysis
* Correlation heatmap
* Target variable distribution
* Box plots
* Outlier analysis

A correlation matrix was generated using the numerical features to understand relationships between variables.

---

 4. Outlier Handling

Outliers were identified using box plots and handled using the **Interquartile Ran**
