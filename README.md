# 📊 Employee Performance and Retention Analysis

> 🤖 Machine Learning + Deep Learning for smarter workforce management  
> 🔍 Real-world employee data analyzed to reveal attrition patterns, performance drivers, and department-level insights.

---

## 🎯 What This Project Does

- ✅ Predicts **if an employee will leave** using Random Forest (accuracy: ~92%)
- ✅ Predicts **how well an employee will perform** using Regression & Neural Nets (R² ≈ 0.78, MAE ≈ 0.11)
- ✅ Identifies **why employees leave** (department-wise attrition, performance correlation)
- ✅ Applies **Bayesian analysis & hypothesis testing** to find significant workforce trends

---

## 📁 Dataset Overview

| Feature             | Description                             |
|---------------------|-----------------------------------------|
| EmployeeID, Name    | Identifier columns                      |
| Age, Salary         | Numeric features                        |
| Department          | Categorical feature                     |
| YearsAtCompany      | Experience duration                     |
| PerformanceScore    | Target for regression                   |
| Attrition (Yes/No)  | Target for classification               |

📍 Data cleaned: duplicates removed, missing numeric values filled (mean), categorical values standardized.

---

## 🧠 Techniques Used

| Stage                  | Methods / Tools                      |
|------------------------|--------------------------------------|
| EDA & Stats            | `pandas`, `seaborn`, `matplotlib`    |
| Probability & Bayes    | Conditional probabilities, ANOVA     |
| ML: Attrition Classifier | `RandomForestClassifier` (92% acc) |
| ML: Performance Regressor | `LinearRegression` (R² ~0.78)     |
| DL: Performance        | Keras Neural Network (MAE ≈ 0.11)    |
| DL: Attrition          | Keras Binary Classifier (91% acc)    |

---

## 📈 Visual Highlights

- 📉 **Line Plot**: `YearsAtCompany` vs `PerformanceScore`
- 📊 **Bar Chart**: Department-wise attrition count
- 🔵 **Scatter Plot**: `Salary` vs `PerformanceScore` (colored by `Attrition`)
- 🧊 **Correlation Heatmap**: Feature relationships
- 📦 **Boxplots**: Outlier detection

---

## 🔍 What We Learned

- 💰 **Salary** and ⏳ **YearsAtCompany** strongly correlate with performance
- 🧠 **R&D** has the highest average performance
- 🚨 **HR** has the highest attrition rate (~33%)
- 📊 Performance significantly differs across departments (ANOVA p < 0.05)

---

## ✅ Requirements

- Python 3.10.0
- Jupyter Notebook
- Libraries:
  - pandas, numpy, matplotlib, seaborn
  - scikit-learn
  - tensorflow / keras

---

## ✅ Project Outcome

This project provides:

- 🔍 A predictive lens on which employees may leave
- 🧠 Insights into improving retention and performance
- 📊 Data-driven strategies for HR decision-making

---

## 📂 Included Files

- `Employee_data.csv` – Dataset
- `employee_analysis.ipynb` – Full project code (EDA → ML → DL)
- `README.md` – Project summary

---

> Made with 💻 and ☕ by **Kritish Dhiman** — drop a ⭐ if you found it helpful!
