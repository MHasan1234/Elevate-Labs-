# Logistic Regression on Breast Cancer Dataset

This project demonstrates a complete machine learning workflow using Logistic Regression to classify malignant and benign tumors using the Breast Cancer Wisconsin dataset.

---

## 📂 Files

- `Logistic_Regression_Breast_Cancer.ipynb` — Main notebook with code, plots, and analysis.
- `data.csv` — Input dataset.
- `README.md` — Project overview and usage instructions.

---

## 🧬 Dataset Overview

- Diagnostic measurements from breast cancer biopsy images.
- Target variable:
  - `M` → Malignant (1)
  - `B` → Benign (0)

Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

---

## 🧪 Workflow Summary

1. **Data Cleaning**: Removed IDs and unnamed columns, mapped targets.
2. **Feature Scaling**: Used `StandardScaler` to normalize features.
3. **Model**: Trained Logistic Regression on training data.
4. **Evaluation**: 
   - Accuracy, Precision, Recall, F1
   - Confusion Matrix
   - ROC-AUC
5. **Threshold Tuning**: Explored effects of lowering classification threshold.

---

## 🧾 Evaluation Metrics

- **Accuracy**: ~97%
- **ROC-AUC Score**: ~0.99
- **Precision/Recall Tradeoff** handled via threshold tuning.

---

## 📊 Visualizations

### ✅ Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

> True Negatives and True Positives are dominant — great model fit.

---

### 📈 ROC Curve

![ROC Curve](images/roc_curve.png)

> Area under the curve (AUC) is close to 1, indicating excellent performance.

---

## 🧠 Sigmoid Function

The logistic regression model uses the sigmoid function:


This function maps any linear combination of inputs to a value between 0 and 1 — representing probability.

---

## 📦 Requirements

Install with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
