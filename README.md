# Customer Churn Prediction & Customer Segmentation

## Overview

This project predicts customer churn using Machine Learning and segments customers into different groups using clustering techniques.

The objective is to identify customers likely to leave the service and help businesses improve customer retention strategies.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Random Forest Classifier
* K-Means Clustering
* Matplotlib
* Seaborn

---

## Workflow

1. Data Cleaning
2. Missing Value Handling
3. Feature Engineering
4. One-Hot Encoding
5. Train-Test Split
6. Random Forest Training
7. Hyperparameter Tuning
8. Cross Validation
9. ROC-AUC Evaluation
10. Customer Segmentation using K-Means

---

Project Structure
-> CBSOT.ipynb
-> churn_model.pkl
-> confusion_matrix.png
-> feature_importance.png
-> segmentation.png
-> README.md

and

Results
- Validation Accuracy: ~98%
- Cross Validation Accuracy: ~98%
- ROC-AUC Score: 1.0
- 4 Customer Segments Generated using K-Means
---

## Features

* Customer Churn Prediction
* Customer Segmentation
* Feature Importance Analysis
* High Risk Customer Identification

---
## Dataset

The project uses the IBM Telco Customer Churn Dataset.

The original dataset is included in the repository:

📂 data/Telco_customer_churn.xlsx

It contains 7,043 customer records and 33 business attributes including customer demographics, subscription details, billing information, and churn status.
---
## Files

* CBSOT.ipynb
* churn_model.pkl
* Telco_customer_churn.xlsx

---

## Future Enhancements

* Streamlit Deployment
* Real-Time Prediction
* Interactive Dashboard

Dataset and generated customer segment files are not uploaded due to GitHub file size limitations.
