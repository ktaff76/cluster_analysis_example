# 👥 Employee Attrition Cluster Analysis

## 📌 Overview
This project applies **unsupervised machine learning** techniques to analyze employee attrition patterns using clustering. The goal is to identify distinct employee groups and understand their attrition tendencies for better HR decision-making.

---

## 🛠️ Tech Stack
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- scipy

---

## ✅ Dataset
- Source: WA_Fn-UseC_-HR-Employee-Attrition.csv
- Target Variable: Attrition (Yes/No)

---

## 🔍 Implementation Steps
1. Data preprocessing: categorical encoding, scaling, PCA.
2. Cluster analysis using K-Means.
3. Optimal clusters determined using Elbow Method.
4. Feature importance analysis using RandomForestClassifier.

---

## 📈 Visualizations
- Elbow Curve for optimal clusters
- Cluster distribution by attrition
- Feature importance bar chart

---

## ✅ Key Insights
- Employees in Cluster 1 have twice the attrition risk compared to Cluster 0.
- MonthlyIncome, Age, and DistanceFromHome are top predictors of attrition.

---

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/employee-attrition-cluster-analysis.git
pip install -r requirements.txt
jupyter notebook employee_attrition_cluster_analysis.ipynb
```
