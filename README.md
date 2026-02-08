# 🫀 Heart Disease Prediction  
### Machine Learning – Assignment 2

---

## 1. Problem Statement

The objective of this project is to build and compare multiple machine learning classification models to predict the presence of **heart disease** using patient clinical data.  
The models are evaluated using standard performance metrics to identify the most reliable algorithm for medical diagnosis support.

---

## 2. Dataset Details (Size & Source)

- **Dataset Name:** Heart Disease Dataset  
- **Source:** UCI Machine Learning Repository / Kaggle (Public dataset)  
- **Number of Instances:** ~900 patient records  
- **Number of Features:** 12+ clinical attributes  
- **Target Variable:** `HeartDisease`  
  - `1` → Heart disease present  
  - `0` → No heart disease  

The dataset includes clinical features such as age, sex, chest pain type, cholesterol level, resting blood pressure, ECG results, maximum heart rate, and exercise-induced angina.

---

## 3. Models Implemented

The following machine learning classification models were implemented:

- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Random Forest (Ensemble Model)  
- XGBoost (Ensemble Model)  

---

## 4. Model Performance Metrics Comparison

| ML Model Name        | Accuracy | AUC    | Precision | Recall | F1-score | MCC   |
|---------------------|----------|--------|-----------|--------|----------|-------|
| Logistic Regression | 0.8750   | 0.8959 | 0.8559    | 0.9314 | 0.8920   | 0.7480 |
| Decision Tree       | 0.7880   | 0.7861 | 0.8119    | 0.8039 | 0.8079   | 0.5716 |
| KNN                 | 0.6957   | 0.7500 | 0.7255    | 0.7255 | 0.7255   | 0.3840 |
| Naive Bayes         | 0.8913   | 0.9280 | 0.8942    | 0.9118 | 0.9029   | 0.7797 |
| Random Forest       | 0.8750   | 0.9235 | 0.8762    | 0.9020 | 0.8889   | 0.7465 |
| XGBoost             | 0.8696   | 0.9230 | 0.8980    | 0.8627 | 0.8800   | 0.7380 |

---

## 5. Observations on Model Performance

| Model Name | Observation |
|-----------|-------------|
| **Logistic Regression** | Provided a strong baseline performance and worked well for linearly separable patterns. |
| **Decision Tree** | Easy to interpret but showed sensitivity to data variations and potential overfitting. |
| **KNN** | Performance depended heavily on feature scaling and the choice of k value. |
| **Naive Bayes** | Performed efficiently with probabilistic assumptions and handled feature independence well. |
| **Random Forest** | Delivered robust performance by reducing overfitting through ensemble learning. |
| **XGBoost** | Achieved the best overall performance due to boosting, regularization, and optimized learning. |

---

## 6. Evaluation Metrics Used

- Accuracy  
- Precision  
- Recall  
- F1-score  
- AUC (Area Under ROC Curve)  
- Matthews Correlation Coefficient (MCC)  

---

## 7. Streamlit Application Features

- CSV dataset upload option  
- Model selection dropdown  
- Display of evaluation metrics  
- Confusion matrix visualization  

---

## 8. How to Run the Application

```bash
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

Open in browser:
```
http://localhost:8501
```

---

## 9. Conclusion

This project demonstrates an end-to-end machine learning workflow including data preprocessing, model training, evaluation, and deployment using Streamlit.  
Among all evaluated models, **Naive Bayes and XGBoost** showed strong and reliable performance for heart disease prediction.

---

## 10. Project Status

✔ All required models implemented  
✔ All evaluation metrics calculated  
✔ Streamlit app fully functional  
 
