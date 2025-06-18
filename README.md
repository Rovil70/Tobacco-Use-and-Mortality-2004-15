# 🚬 Tobacco Use and Mortality Analysis (2004–2015)

## 📌 Project Overview

This project analyzes the impact of tobacco use on health outcomes such as hospital admissions and mortality using datasets from 2004 to 2015. The goal is to discover patterns, model risk factors, and provide actionable insights using Machine Learning and Data Visualization.

---

## 📁 Datasets Used

| File Name         | Description                                      |
|------------------|--------------------------------------------------|
| `admissions.csv` | Year-wise tobacco-related hospital admissions    |
| `fatalities.csv` | Tobacco-related deaths per year                  |
| `metrics.csv`    | Health, income, and socio-economic metrics       |
| `prescriptions.csv` | Tobacco cessation prescriptions and costs    |
| `smokers.csv`    | Smoking rates by state, year, age, and gender    |

---

## 🚦 Project Workflow

### ✅ Phase 1: Data Cleaning & Preprocessing
- Loaded all 5 datasets
- Handled missing values and standardized formats
- Cleaned column names and saved preprocessed versions

### 📊 Phase 2: Exploratory Data Analysis (EDA)
- Analyzed smoking rate trends, fatalities, and admissions
- Created heatmaps, line plots, bar graphs
- Observed that smoking rates have decreased over time

### 🔧 Phase 3: Feature Engineering
- Merged datasets on `Year`
- Created features: `smoking_rate_change`, `prescription_rate`, `fatality_ratio`

### 📈 Phase 4: Regression Modeling
- **Goal**: Predict number of fatalities
- **Models**: Linear Regression, Random Forest
- **Metrics**: RMSE, R² Score

### 🧠 Phase 5: Classification Modeling
- **Goal**: Classify years as High, Medium, Low risk
- **Models**: Logistic Regression, Decision Tree
- **Metric**: Accuracy, Confusion Matrix

### 🎯 Phase 6: Clustering
- Used KMeans clustering and PCA for visualization
- Clustered similar years based on tobacco use trends

---

## 🧠 Key Insights

- Smoking rates have a direct correlation with fatalities and hospital admissions
- Prescription programs show positive impact on reducing tobacco use
- Socio-economic indicators (e.g., income, education) affect tobacco usage

---

## 🧰 Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI / Plotly Dash (optional for dashboard)
- GitHub for version control

---

