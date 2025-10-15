# 🧠 Optimizing Fraud Detection — A Comparative Analysis of Machine Learning Algorithms

Fraud detection is a critical challenge in financial analytics due to large-scale imbalanced data and evolving attack patterns.  
This project applies **Machine Learning (ML)** techniques to detect fraudulent transactions, comparing the performance of various algorithms to identify the most accurate and reliable model.

---

## 🚀 Project Overview

This project demonstrates how supervised and unsupervised learning techniques can be used for **credit card fraud detection**.  
Four algorithms were compared:

- **Decision Tree**
- **Random Forest**
- **K-Means Clustering**
- **Isolation Forest**

After extensive testing, the **Random Forest** model achieved the highest accuracy and recall, making it the most effective for real-world fraud detection scenarios.

---

## 🧩 Methodology

1. **Data Preprocessing**
   - Handled class imbalance and missing values.
   - Performed normalization and feature scaling.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed transaction distributions and correlations.
   - Visualized fraud vs. non-fraud patterns.

3. **Model Development**
   - Trained Decision Tree, Random Forest, K-Means, and Isolation Forest.
   - Optimized parameters using Grid Search.

4. **Evaluation**
   - Compared models based on Accuracy, Precision, Recall, and F1-score.
   - Random Forest outperformed others in both accuracy and generalization.

---

## ⚙️ Tools & Libraries Used

| Category | Tools / Libraries |
|-----------|-------------------|
| Language | Python |
| IDE | Jupyter Notebook |
| Data Handling | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Documentation | Word, PowerPoint, GitHub |

---

## 📊 Key Results

| Model | Type | Accuracy | Precision | Recall | F1-Score |
|-------|------|-----------|------------|---------|-----------|
| Random Forest | Supervised | ⭐ Highest | High | High | High |
| Decision Tree | Supervised | Moderate | Moderate | Moderate | Moderate |
| K-Means | Unsupervised | Low | – | – | – |
| Isolation Forest | Unsupervised | Moderate | – | – | – |

📈 **Conclusion:**  
Random Forest offers the most reliable performance for identifying fraudulent transactions with minimal false negatives.

---

## 📁 Repository Structure

