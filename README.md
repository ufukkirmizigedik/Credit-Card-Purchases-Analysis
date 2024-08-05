Credit Card Purchases Analysis

Overview

This project involves analyzing credit card purchase data to gain insights into spending patterns across different categories and demographic groups. The analysis includes trend visualizations, category-wise spending, and predictive modeling to forecast future spending.

Dataset
The dataset used in this project is available for download from Kaggle:

Credit Card Transaction Records Dataset: https://www.kaggle.com/datasets/muhammadehsan000/credit-card-transaction-records-dataset
The dataset contains transactional data including the date, amount spent, category, gender, and job information of the credit card holders.

Libraries Used

pandas: For data manipulation and analysis.
matplotlib: For creating visualizations.
seaborn: For statistical data visualization.
scikit-learn: For building and evaluating the predictive model.
numpy: For numerical operations.

Analysis
The analysis involves the following steps:

Data Preprocessing:

Read the dataset and convert the trans_date_trans_time column to datetime format.
Extract the year from the transaction date for yearly aggregation.

Exploratory Data Analysis (EDA):

Analyze total spending by category and visualize using area plots.
Compare spending patterns across genders using bar plots.
Analyze spending trends over the years by category.

Predictive Modeling:

Encode categorical data and build a linear regression model to predict future spending amounts by category for the year 2021.
Output the predicted amounts for different categories.

Insights:

Identify the job with the highest total spending amount.
Display the top 10 jobs based on spending.
Usage
To run the analysis and visualize the results, follow these steps:

Download the Dataset:

Download the dataset from Kaggle: Credit Card Transaction Records Dataset.
