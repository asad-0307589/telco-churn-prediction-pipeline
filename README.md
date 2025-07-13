# 📊 Telco Customer Churn Prediction Pipeline

This project builds a **production-ready machine learning pipeline** to predict customer churn using the **Telco Customer Churn Dataset**.

---

## 🎯 Objective

The main objective is to:
- Predict whether a customer will churn (i.e., stop using the service).
- Build a **reusable, exportable ML pipeline** that automates data preprocessing, model training, and prediction.
- Apply **hyperparameter tuning** to select the best model settings for improved accuracy.

---

## ⚙️ Methodology / Approach

 **Data preprocessing**:  
- Handled missing values using imputation.
- Scaled numerical features with `StandardScaler`.
- Encoded categorical features with `OneHotEncoder`.

 **Pipeline construction**:  
- Used `Pipeline` and `ColumnTransformer` to combine preprocessing and modeling steps.

 **Model training**:  
- Focused on **Logistic Regression** for classification.
- Tuned hyperparameters (regularization strength `C`) using **GridSearchCV** with cross-validation.

 **Evaluation & export**:  
- Evaluated the final model using accuracy and classification report.
- Exported the best pipeline as a `.joblib` file for reuse in production.

---

## 📊 Key results or observations

- The best hyperparameter (`C`) was selected automatically via GridSearchCV.
- Achieved an accuracy of around **80–82%** on the test set (actual result may vary based on dataset split).
- The final pipeline can be directly loaded and used to make predictions on new customer data.

---

##  Summary

This project demonstrates:
- Building an **end-to-end ML pipeline**.
- Automating preprocessing and training in a single object.
- Applying **hyperparameter tuning** and ensuring the model is **production-ready**.

<img width="538" height="212" alt="image" src="https://github.com/user-attachments/assets/a6da7164-e6e0-4761-b28c-7c61967631fc" />


