# Heart Disease Prediction & Clustering

This project applies **machine learning** techniques to the [UCI Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease).  
It explores both **supervised learning (classification)** and **unsupervised learning (clustering)** to detect and analyze patterns related to heart disease.

## 🎯 Objectives

### 🔹 Supervised Learning – Classification
- **Algorithms:** Logistic Regression, Decision Tree, Random Forest, SVM  
- **Workflow:**
  1. Data preprocessing (scaling, encoding, missing values)
  2. Dimensionality reduction (PCA)
  3. Feature selection (mutual information)
  4. Model training with `GridSearchCV`
- **Metrics:** Accuracy, Precision, Recall, F1-score, ROC Curve & AUC  
- **Deliverables:** Trained models saved in `models/`

### 🔹 Unsupervised Learning – Clustering
- **KMeans Clustering:**  
  - Tested multiple `k` values using **silhouette score**  
  - Best `k` automatically selected  
- **Hierarchical Clustering:**  
  - Dendrogram visualization  
  - Cluster assignment with Agglomerative Clustering  
- **Deliverables:** Saved models (`kmeans_best.pkl`, `hierarchical_best.pkl`) and results in CSV

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository – Heart Disease  
- **Features:** 13 clinical and demographic attributes (age, sex, cholesterol, blood pressure, etc.)  
- **Target:** Binary classification  
  - `0 = No Heart Disease`  
  - `1 = Heart Disease Present`

---

## 🛠️ Tools & Libraries

- **Python 3.x**
- **Data Processing:** pandas, numpy  
- **Visualization:** matplotlib, seaborn, scipy (dendrograms)  
- **ML Models & Pipelines:** scikit-learn  
- **Model Saving:** joblib  

---
