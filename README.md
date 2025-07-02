# 🔍 Predictive Modeling using Supervised Classification Algorithms

This project applies and compares multiple supervised machine learning classification algorithms on an imbalanced dataset to identify the best-performing model.

---

## 📊 Goal

Build and evaluate classification models to predict a binary outcome, with a focus on:
- Handling class imbalance
- Evaluating performance beyond accuracy (using F1, precision, recall)
- Selecting the most effective algorithm for deployment

---

## 🛠️ Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest 
- K-Nearest Neighbors (KNN)
- Support Vector Machine (LinearSVC)
- XGBoost 

---

## ⚙️ Techniques Used
- **Data Preprocessing**: Label encoding, scaling, and train-test split  
- **Imbalance Handling**: stratified sampling, smote
- **Model Evaluation**: Accuracy, F1 score, confusion matrix, classification report, roc auc rurve, pr curve
- **Cross-Validation**: Stratified K-Fold CV  
- **Hyperparameter Tuning**: `RandomizedSearchCV`

---

## 🏆 Results Summary

| Model                  | Accuracy | F1 Score (Positive) | Notes                                |
|------------------------|----------|----------------------|--------------------------------------|
| Logistic Regression    | 0.75     | 0.37                 | High recall, low precision           |
| Decision Tree          | 0.52     | 0.20                 | Underfitting                         |
| Random Forest          | 0.83     | 0.44                 | Best F1 score (balanced model)       |
| KNN                    | 0.81     | 0.33                 | Moderate results                     |
| SVM (LinearSVC)        | 0.75     | 0.37                 | High recall, low precision           |
| **XGBoost**            | **0.89** | **0.38**             | Best accuracy, strong performance    |

📌 Final choice: **XGBoost** for its high accuracy and general robustness  
📌 Alternative: **Random Forest** for best F1 score and interpretability


