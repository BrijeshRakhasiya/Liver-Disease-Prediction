# 🩺 Liver Disease Prediction (Indian Liver Patient Dataset)

**Dataset:** Indian Liver Patient Records — 583 samples (416 with liver disease, 167 without), 10 features  
**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records) | [UCI Repository](https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29)

---

## 🎯 Objective

Build a binary classification model to predict the presence of liver disease using patient biochemical data.

---

## 📂 Project Overview

- **Data:** `indian_liver_patient.csv`
- **Preprocessing:**
  - Handled missing values
  - Gender label encoding
  - Standardized features using `StandardScaler`
- **Model:** Machine Learning Classifier
- **Metrics:**
  - **Accuracy:** `0.7617`
  - **AUC-ROC:** `0.7916`
  - **Loss:** `0.4650`

---

## 🛠️ Workflow

1. Import dataset
2. Handle missing/null values
3. Encode categorical features (Gender)
4. Feature scaling using `StandardScaler`
5. Train/Test split
6. Model training (e.g., Logistic Regression, Random Forest, etc.)
7. Evaluation with Accuracy, AUC-ROC, and Loss
8. Visualizations: ROC Curve, Confusion Matrix

---

## 📊 Results Summary

| Metric     | Value    |
|------------|----------|
| Accuracy   | 0.7617   |
| AUC‑ROC    | 0.7916   |
| Loss       | 0.4650   |

---

## 🚀 How to Use

```bash
# Clone the repository
git clone https://github.com/BrijeshRakhasiya/Liver-Disease-Prediction.git

# Install dependencies
pip install numpy pandas scikit-learn tensorflow plotly

# Run the notebook
jupyter notebook liver-disease-prediction.ipynb
```
# 🙋‍♂️ Author
Brijesh Rakhasiya
AI/ML Enthusiast | Data Scientist | Problem Solver


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**e.
