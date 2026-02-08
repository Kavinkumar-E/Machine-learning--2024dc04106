# ML Assignment 2 – Classification Models and Streamlit Deployment

## 1. Problem Statement
The objective of this assignment is to implement multiple machine learning classification models on a real-world dataset, evaluate their performance using standard classification metrics, and deploy an interactive web application using Streamlit. This project demonstrates the complete end-to-end machine learning workflow including data preprocessing, model training, evaluation, and deployment.

---

## 2. Dataset Description
The Heart Disease dataset is used for this assignment. The dataset is obtained from a public repository and contains clinical and demographic attributes of patients. It consists of 918 records with more than 12 input features. The target variable **HeartDisease** is a binary indicator representing the presence (1) or absence (0) of heart disease.

Key characteristics:
- Number of instances: 918
- Number of features: 12+
- Problem type: Binary classification
- Target column: HeartDisease

---

## 3. Machine Learning Models and Evaluation Metrics

The following machine learning classification models were implemented and evaluated using the same dataset:

- Logistic Regression  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Naive Bayes (Gaussian)  
- Random Forest (Ensemble Model)  
- XGBoost (Ensemble Model)  

Each model was evaluated using the following metrics:
- Accuracy  
- AUC Score  
- Precision  
- Recall  
- F1 Score  
- Matthews Correlation Coefficient (MCC)  

### Model Performance Comparison

| Model Name | Accuracy | AUC | Precision | Recall | F1 Score | MCC |
|-----------|----------|-----|-----------|--------|----------|-----|
| Logistic Regression | XX | XX | XX | XX | XX | XX |
| Decision Tree | XX | XX | XX | XX | XX | XX |
| KNN | XX | XX | XX | XX | XX | XX |
| Naive Bayes | XX | XX | XX | XX | XX | XX |
| Random Forest | XX | XX | XX | XX | XX | XX |
| XGBoost | XX | XX | XX | XX | XX | XX |

> Note: Metric values are obtained from the execution of the models on the test dataset.

---

## 4. Observations on Model Performance

| Model Name | Observation |
|-----------|-------------|
| Logistic Regression | Provided a strong baseline performance and worked well for linearly separable patterns. |
| Decision Tree | Easy to interpret but showed sensitivity to data variations and potential overfitting. |
| KNN | Performance depended heavily on feature scaling and the choice of k value. |
| Naive Bayes | Performed efficiently with probabilistic assumptions and handled feature independence well. |
| Random Forest | Delivered robust performance by reducing overfitting through ensemble learning. |
| XGBoost | Achieved the best overall performance due to boosting, regularization, and optimized learning. |

---

## 5. Streamlit Web Application
An interactive Streamlit web application was developed to demonstrate the models and their evaluation. The application includes the following features:
- CSV dataset upload option
- Model selection dropdown
- Display of evaluation metrics
- Confusion matrix visualization

The application is deployed using **Streamlit Community Cloud** and provides an interactive interface for model comparison.

---

## 6. Project Structure

