# Predictive-Analytics-and-Recommendation-Systems-in-Banking

Predictive-Analytics-and-Recommendation-Systems-in-Banking

Introduction

This project focuses on predicting Loan Defaults using Supervised Learning, Segmenting Customers with Unsupervised Learning, and Recommending Bank Products through a Recommendation Engine.

Technologies Used:

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Streamlit

Pickle

Scipy

Surprise

Installation

pip install pandas

pip install numpy

pip install scikit-learn

pip install matplotlib

pip install seaborn

pip install streamlit

pip install pickle

pip install scikit-surprise

Data Collection

Synthetic data is generated using the Faker Python library

Loan Default Prediction: Customer demographics, loan amounts, interest rates, and repayment status.

Customer Segmentation: Transaction details including amounts, types, and dates.

Loan Default Prediction: Customer interactions with various banking products.

Data Understanding

Identify Variable Types

Handle Invalid Values

Data Preprocessing

Handle Missing Values using Mean, Median, Mode.

Detect Outliers using IQR or Isolation Forest.

Determine Skewnes Using Log, sqrt or Box-Cox transformations.

Encode Categorical Variables with One-Hot Encoding, Label Encoding, or Ordinal Encoding.

Exploratory Data Analysis

Visualize Outliers and Skewness with Boxplot, Distplot or Violin plots.

Analyze and Treat Skewness.

Feature Engineering

Create New Features through Aggregation or Transformation.

Drop highly correlated columns using heatmaps.

Model Building and Evaluation

Split Data

Model Training and Evaluate:

Loan Default Prediction: Use Classification models- Logistic Regression,Decision Tree Clasifier, Random Forest Classifier,Gradient Boosting. Metrics: Accuracy, Precision, Recall, F1 score.

Customer Segmentation: Use Clustering Algorithms- KMeans, DBscan, Hierarchical Clustering to segment customers based on transaction behavior. Metrics: Silhouette scores and Davies-Bouldin index to evaluate cluster quality
Product Recommendations: Use Collavorative filtering or Content-Based Filtering Algorithms. Metrics: Precision, Recall, Mean Average Precision(MAP), Normalized Discounted Cumulative Gain score.

Optimize with Hyperparameter Tuning: Use Cross-Validation and Grid Search.

Model GUI

Develop a Streamlit App for interactive predictions, customer segmentations and product recommendations.

Allow the users to input feature values and display predictions, customer segmentations and product recommendations.

Usage

Steps to be followed for effectively using the application:

Access the Streamlit App: Open the application in your browser.

Select target: Choose from options such as Loan Default Prediction or Customer Segmentation or Product Recommendations from the Navigation menu.

Input Data:

For Loan Default Prediction: Input customer informations.

For Customer Segmentation: Provide Transaction details.

For Product Recommendations: Input customer interaction data

Perform Prediction: By clicking the button will able to get results based on the input data.

Results: The Prediction output will be displayed on the page, allowing you to analyze loan default risks, customer segments, or recommended products.

Features

Data Preprocessing: Handles missing values,outliers, and skewness.

Model Training: Trains Machine Learning Models with hyperparameter optimization.

Interactive GUI: Provides a user-friendly web interface for viewing predictions based on user input.

Interactive Visualizations: Utilizes EDA techniques to understand data distributions and model performance.

Pickle Integration: Saves and loads models and transformers for seamless use.
