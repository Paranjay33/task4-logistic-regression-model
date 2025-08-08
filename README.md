# Logistic Regression Binary Classifier

## 📌 Objective
Build a binary classifier using Logistic Regression to predict breast cancer diagnosis.

## 🛠 Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib

## 📂 Dataset
**Breast Cancer Wisconsin Dataset** — [Download Link](https://raw.githubusercontent.com/plotly/datasets/master/data.csv)

## 📋 Steps Performed
1. Loaded dataset and cleaned missing values.
2. Split data into training and testing sets.
3. Standardized features using `StandardScaler`.
4. Trained Logistic Regression model.
5. Evaluated model using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
6. Plotted ROC Curve for visualization.

## 📊 Results
- **Precision:** ~0.97
- **Recall:** ~0.95
- **ROC-AUC:** ~0.99

## 📎 How to Run
```bash
pip install scikit-learn pandas matplotlib
