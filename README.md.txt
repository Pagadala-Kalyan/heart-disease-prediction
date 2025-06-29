# 🫀 Heart Disease Prediction (Logistic Regression)

This is a beginner-friendly machine learning project that uses **Logistic Regression** to predict whether a person is likely to have heart disease based on health data. The project is based on the **Cleveland Heart Disease dataset**.

---

## 📂 Dataset

- **Source:** [Kaggle - Heart Disease Cleveland UCI](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Instances:** 303 patients
- **Features:** 13 medical attributes (age, sex, cholesterol, etc.)
- **Target Variable:** `condition`  
  - `0`: No heart disease  
  - `1`: Has heart disease (converted from original labels)

---

## 🧠 Objective

To build a **classification model** that can predict the presence of heart disease using simple preprocessing and logistic regression.

---

## 🧵 Workflow Summary

1. Load and clean the dataset
2. Split features into:
   - **Numerical:** `age`, `chol`, `oldpeak`, etc.
   - **Categorical:** `sex`, `cp`, `thal`, etc.
3. Preprocessing:
   - Used `StandardScaler` for numeric features
   - Used `OneHotEncoder` for categorical features (`handle_unknown='ignore'`)
4. Combined preprocessing and model into a `Pipeline`
5. Evaluated using 5-fold cross-validation (`cross_validate`)

---

## 📈 Model Performance

| Model              | Cross-Validation Accuracy |
|-------------------|---------------------------|
| Logistic Regression | **~80%** ✅ |

- Consistent performance across folds
- Simple model with good baseline accuracy

---

## 📌 Libraries Used

- `pandas`, `numpy`
- `scikit-learn` (`LogisticRegression`, `Pipeline`, `ColumnTransformer`, `StandardScaler`, `OneHotEncoder`, `cross_validate`)


