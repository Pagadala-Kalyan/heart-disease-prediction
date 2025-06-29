# 🫀 Heart Disease Prediction

A beginner-friendly machine learning project using **Logistic Regression** to predict the presence of heart disease based on clinical data from the Cleveland dataset.

---

## 📂 Dataset

- **Source:** [Heart Disease - Cleveland UCI (Kaggle)](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Format:** 303 records, 13 features + 1 target
- **Target:** `condition` (0 = no heart disease, 1 = heart disease)

---

## 🔧 Tools & Libraries

- Python
- pandas, numpy
- scikit-learn (LogisticRegression, Pipeline, ColumnTransformer, OneHotEncoder, StandardScaler)

---

## 🧵 Workflow Summary

1. Data loading and cleaning
2. Categorical & numerical feature separation
3. Preprocessing:
   - Scaling with `StandardScaler`
   - Encoding with `OneHotEncoder` (`handle_unknown='ignore'`)
4. Pipeline: Preprocessing + `LogisticRegression`
5. Evaluation using 5-fold cross-validation

---

## 📈 Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~80% ✅ |

> A simple model with consistent performance on tabular medical data.

---

## 🧠 Author

- **Kalyan Pagadala**  
  M.Tech CSE Student | ML Enthusiast

---

## 📃 License

No license added. This project is for academic and learning purposes.
