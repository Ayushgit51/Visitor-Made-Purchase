# Visitor Made Purchase Prediction

## Project Description
This project focuses on predicting whether a website visitor will make a purchase based on user behavior and session-level features. The model is designed to support data-driven decision making in e-commerce by identifying high-intent visitors.

---

## Problem Statement
Given historical visitor interaction data, the objective is to build a classification model that accurately predicts purchase outcomes.

---

## Prediction Objective
- **Target Variable:** Purchase (Binary: Yes / No)
- The model predicts the likelihood of a visitor completing a purchase during a session.

---

## Machine Learning Approach
The project applies supervised learning techniques with an emphasis on model generalization and reliability.

### Algorithms Implemented
- Decision Tree Classifier  
- Logistic Regression  
- Random Forest (for performance comparison)

---

## Decision Tree Pruning
To reduce overfitting and improve test performance, cost-complexity pruning is applied to the Decision Tree model.  
Pruning removes weak splits and limits unnecessary tree growth, resulting in a more robust and interpretable model.

---

## Cross Validation
K-Fold Cross Validation is used to ensure consistent performance across different data splits.  
This approach provides a more reliable evaluation than a single train-test split.

---

## Model Workflow
1. Data preprocessing and feature engineering  
2. Train-test split  
3. Model training  
4. Pruning and cross-validation  
5. Model evaluation  

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

---

## Tools and Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## Author
Ayush Kumar  
Data Science and Machine Learning Enthusiast

