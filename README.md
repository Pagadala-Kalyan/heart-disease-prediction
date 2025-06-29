# 🫀 Heart Disease Prediction

A beginner-friendly machine learning project using **Logistic Regression** to predict the presence of heart disease based on clinical data from the Cleveland dataset.

---

## 📂 Dataset

- **Source:** [Heart Disease - Cleveland UCI (Kaggle)](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Format:** 303 records, 13 features + 1 target
- **Target:** `condition` (0 = no heart disease, 1 = heart disease)

  
---

## 🧾 Feature Description

There are 13 attributes:

- `age`: age in years  
- `sex`: sex (1 = male; 0 = female)  
- `cp`: chest pain type  
  - 0: typical angina  
  - 1: atypical angina  
  - 2: non-anginal pain  
  - 3: asymptomatic  
- `trestbps`: resting blood pressure (in mm Hg on admission to the hospital)  
- `chol`: serum cholesterol in mg/dl  
- `fbs`: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
- `restecg`: resting electrocardiographic results  
  - 0: normal  
  - 1: ST-T wave abnormality  
  - 2: probable or definite left ventricular hypertrophy (by Estes' criteria)  
- `thalach`: maximum heart rate achieved  
- `exang`: exercise-induced angina (1 = yes; 0 = no)  
- `oldpeak`: ST depression induced by exercise relative to rest  
- `slope`: slope of the peak exercise ST segment  
  - 0: upsloping  
  - 1: flat  
  - 2: downsloping  
- `ca`: number of major vessels (0–3) colored by fluoroscopy  
- `thal`:  
  - 0 = normal  
  - 1 = fixed defect  
  - 2 = reversible defect  

**Label:**
- `condition`: 0 = no heart disease, 1 = heart disease


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
