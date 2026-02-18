# AI-Based Intrusion Detection System with Power BI Dashboard

# Project Overview

This project develops an AI-powered Intrusion Detection System (IDS) to classify network traffic as either Normal or Attack using Machine Learning.

The results are visualized through an interactive Power BI Cybersecurity Dashboard for monitoring and analysis.

# Objective

Detect malicious network activity using Machine Learning
Evaluate model performance using classification metrics
Visualize security insights using Power BI


# Machine Learning Model

Algorithm Used: Random Forest Classifier

The model was trained on the NSL-KDD dataset, a benchmark dataset for network intrusion detection.

# Model Performance

Accuracy: 99.86%
Precision (Attack Class): 99.94%
Recall (Attack Class): 99.76%

Recall is critical in cybersecurity to minimize missed attacks.


# Power BI Dashboard Features

Attack vs Normal Traffic Distribution
Model Performance KPI Cards (Accuracy, Precision, Recall)
Predicted vs Actual Comparison
High-Risk Traffic Table View

# Technologies Used

Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn
Power BI Desktop


# How to Run the Project

1. Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn

2. Run:
python intrusion_detection.py

3. Open `powerbi_dashboard.pbix` in Power BI Desktop.


# Future Improvements

Add Logistic Regression model comparison
Add ROC Curve visualization
Deploy as a Flask API
Containerize using Docker

# Author 
   Jyotn Joshi 
AI / Machine Learning Postgraduate Student
