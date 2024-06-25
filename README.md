# DSCI 631 Project Proposal

## Introduction
This project involves the analysis of the "Human Resources Data Set" available on Kaggle, created by Dr. Carla Patalano and Dr. Rich Huebner for educational purposes. The goal is to perform HR analytics using this synthetic dataset to extract meaningful insights and apply machine learning models.

## Data Description
The dataset contains various features related to employee details and their performance metrics. Key columns include:
- `Employee_Name`: The name of the employee
- `EmpID`: Employee identification number
- `Salary`: The employee's salary
- `Termd`: Binary identifier indicating whether the employee has been terminated (0 or 1)
- `Position`: The job position/title of the employee
- `Department`: The department to which the employee is assigned
- `ManagerName`: The name of the employee's manager
- `RecruitmentSource`: The source from which the employee was recruited
- `PerformanceScore`: The performance score of the employee
- `EngagementSurvey`: Employee engagement survey results
- `EmpSatisfaction`: Employee satisfaction level
- `SpecialProjectsCount`: The number of special projects the employee is involved in the last 6 months
- `LastPerformanceReview_Date`: The date of the employee's most recent performance review
- `DaysLateLast30`: The number of days the employee was late in the last 30 days
- `Absences`: The number of absences recorded for the employee

## Exploratory Analysis
The initial analysis involves exploring the dataset to identify null values, understand the distribution of features, and visualize the data. The key steps include:
1. Loading the dataset and displaying column names and dimensions.
2. Checking for null values and handling them appropriately.
3. Exploring categorical and numerical features.
4. Visualizing distributions and relationships between key features.

## Visualization
Several visualizations are created to better understand the dataset:
- Distribution of salaries
- Count of terminated employees
- Salary distribution by department
- Employee satisfaction vs. absence
- Employee satisfaction vs. salary
- Correlation heatmap

## Machine Learning Algorithms
The project aims to predict employee termination and performance scores using various machine learning algorithms. The steps include:
1. Preprocessing the data by encoding categorical variables and standardizing numerical features.
2. Applying Principal Component Analysis (PCA) for dimensionality reduction.
3. Training and evaluating models such as Logistic Regression, Random Forest, and Decision Tree.

## Feature Importance
Feature importance is analyzed to understand the contribution of each feature to the prediction models. This involves training a Random Forest classifier and visualizing the importance of features.

## Requirements
To run the project, the following Python packages are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Usage
1. Clone the repository.
2. Ensure all required packages are installed.
3. Load the dataset (HRDataset_v14.csv).
4. Run the Jupyter Notebook cells sequentially to reproduce the analysis and results.

## Conclusion
This project demonstrates the application of HR analytics using a synthetic dataset. Through exploratory analysis, visualization, and machine learning models, we aim to extract insights and predict key outcomes such as employee termination and performance scores.


