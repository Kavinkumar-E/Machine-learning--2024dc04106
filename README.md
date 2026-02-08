# 🫀 Heart Disease Prediction  
### Machine Learning Assignment – 2

## 1. Problem Statement
The objective of this project is to build and compare multiple machine learning classification models to predict the presence of **heart disease** using patient clinical data.  
The goal is to evaluate different algorithms based on standard performance metrics and identify the most reliable model for medical diagnosis support.

---

## 2. Dataset Details (Size & Source)
- **Dataset Name:** Heart Disease Dataset  
- **Source:** UCI Machine Learning Repository / Kaggle (public dataset)  
- **Number of Instances:** ~900 patient records  
- **Number of Features:** 12+ clinical attributes  
- **Target Variable:** `HeartDisease`  
  - `1` → Heart disease present  
  - `0` → No heart disease  

The dataset contains clinical and diagnostic features such as age, sex, chest pain type, cholesterol levels, ECG results, maximum heart rate, and exercise-induced angina.

---

## 3. Models Implemented
- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Random Forest (Ensemble)  
- XGBoost (Ensemble)  

---

## 4. Observations on Model Performance

| Model Name | Observation |
|-----------|-------------|
| **Logistic Regression** | Provided a strong baseline performance and worked well for linearly separable patterns. |
| **Decision Tree** | Easy to interpret but showed sensitivity to data variations and potential overfitting. |
| **KNN** | Performance depended heavily on feature scaling and the choice of k value. |
| **Naive Bayes** | Performed efficiently with probabilistic assumptions and handled feature independence well. |
| **Random Forest** | Delivered robust performance by reducing overfitting through ensemble learning. |
| **XGBoost** | Achieved the best overall performance due to boosting, regularization, and optimized learning. |

---

## 5. Evaluation Metrics Used
- Accuracy  
- Precision  
- Recall  
- F1-score  
- AUC (Area Under ROC Curve)  
- Matthews Correlation Coefficient (MCC)  

---

## 6. Conclusion
This project demonstrates an end-to-end machine learning workflow including data preprocessing, model training, evaluation, and deployment using Streamlit.  
Among all evaluated models, ensemble and probabilistic approaches showed strong performance, with **XGBoost and Naive Bayes** performing particularly well.

---

## 7. How to Run the Application

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

## 8. Project Status
✔ Fully functional  
✔ Metrics verified  

