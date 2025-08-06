# Framingham Heart Disease Prediction

This project focuses on predicting the 10-year risk of coronary heart disease (CHD) using data from the Framingham Heart Study. A logistic regression model is employed to classify individuals based on various health indicators.

## Dataset

The analysis utilizes the `framingham.csv` dataset, which comprises medical information for a cohort of individuals. The primary objective is to predict the `TenYearCHD` variable, a binary indicator representing the likelihood of developing coronary heart disease within a decade.

## Project Workflow

The accompanying Jupyter Notebook LogisticRegression.ipynb  outlines the following key stages of the project:

1.  **Library Imports:** Importing essential Python libraries for data manipulation, machine learning, and data visualization.
2.  **Data Loading:** Loading the `framingham.csv` dataset into a pandas DataFrame for subsequent processing.
3.  **Exploratory Data Analysis:** Examining the dataset's structure, data types, and identifying the presence of missing values.
4.  **Data Preprocessing:** Implementing strategies to handle missing data, such as imputation, to ensure data quality.
5.  **Feature Selection:** Identifying and selecting the relevant features and the target variable for the predictive model.
6.  **Data Splitting:** Dividing the dataset into distinct training and testing sets to evaluate the model's generalization capability.
7.  **Model Training:** Training a Logistic Regression model on the prepared training data.
8.  **Model Prediction:** Generating predictions on the unseen test data using the trained model.
9.  **Model Evaluation:** Assessing the model's performance through appropriate metrics, including accuracy and the confusion matrix.
10. **Visualization:** Creating a heatmap visualization of the confusion matrix to provide a clear overview of classification results.

## Execution Instructions

To execute the code and replicate the analysis, please follow these steps:

1.  Clone this repository to your local machine.
2.  Ensure you have a compatible Python environment installed.
3.  Navigate to the project directory in your terminal.
4.  Install the required dependencies by running the following command:
   pip install -r requirements.txt
