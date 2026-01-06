


# Diabetes Outcome Prediction: Linear vs Non-Linear Regression with Model Diagnostics

## 📌 Project Overview
This project presents a comprehensive regression analysis on the **Diabetes dataset** to predict disease progression outcomes.  
It compares **statistical linear models** with **non-linear machine learning models**, emphasizing **interpretability, diagnostics, and generalization performance**.

The study progresses from simple linear regression to multivariate modeling and finally to gradient boosting, supported by rigorous diagnostics and learning-curve analysis.

---

## 🎯 Objectives
- Analyze the relationship between clinical predictors and diabetes progression
- Compare **OLS regression** and **XGBoost** for predictive performance
- Evaluate model assumptions using diagnostic plots
- Study model behavior under varying training set sizes
- Identify strong individual predictors through single-feature analysis

---

## 📂 Dataset
- **Source:** Hastie et al. (LARS) Diabetes Dataset  
  https://hastie.su.domains/Papers/LARS/diabetes.data
- **Target Variable:** Quantitative measure of diabetes disease progression (`Y`)
- **Predictors:** Standardized clinical variables including BMI, blood pressure, and serum measurements

> 📌 The dataset is loaded directly from the public URL to ensure reproducibility.

---

## 🧠 Methodology
The analysis follows a structured, step-by-step modeling pipeline:

### 1. Linear Regression (OLS)
- Single-feature regression (BMI → Y)
- Multiple regression (BMI + S5 → Y)
- Full multivariate regression (all predictors)
- Statistical interpretation using OLS summaries

### 2. Model Diagnostics
- Residuals vs fitted plots
- Partial regression plots (individual feature effects)
- Assumption checking (linearity, homoscedasticity)

### 3. Learning Curve Analysis
- Model performance evaluated across varying training sizes
- Training vs validation MSE trends analyzed

### 4. Non-Linear Modeling
- XGBoost regression to capture non-linear relationships
- Comparison against OLS under identical data conditions

### 5. Feature Analysis
- Single-feature regression for all predictors
- Identification of the best standalone predictor

---

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² (Coefficient of Determination)**

Both training and validation metrics are reported to assess generalization.

---

## 🗂 Repository Structure
├── data/
│ └── README.md # Dataset details and source
├── notebooks/
│ ├── README.md # Notebook descriptions
│ └── diabetes_regression_analysis.ipynb
├── .gitignore
├── LICENSE
└── README.md


---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Statsmodels
- XGBoost
- Matplotlib

---

## 🔍 Key Takeaways
- Linear models provide strong interpretability but are limited in capturing complex patterns
- XGBoost demonstrates improved predictive performance, especially with larger training sizes
- Diagnostic plots are essential for validating regression assumptions
- Feature-level analysis helps guide effective model design

---

## ⚠️ Disclaimer
This project is for **educational and analytical purposes only** and does not constitute medical or clinical advice.

---

## 📌 Author
**Arifa Farhath**  
Data Science Graduate | Statistical Modeling & Machine Learning

