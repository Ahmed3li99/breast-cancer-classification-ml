# Breast Cancer Classification using Machine Learning

This project applies machine learning techniques to classify tumors as malignant or benign using the Breast Cancer dataset from scikit-learn.

---

## Project Overview

The objective of this project is to build and evaluate machine learning models for medical classification. The project includes data preprocessing, feature selection, model training, and performance evaluation.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The dataset used is the Breast Cancer Wisconsin dataset provided by scikit-learn. It contains 569 samples with 30 features describing characteristics of cell nuclei.

---

## Models Used

- Decision Tree Classifier
- Logistic Regression

---

## Evaluation Metrics

- Accuracy
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Results

- **Decision Tree**: Accuracy = 91.23%, ROC-AUC = 0.9206
- **Logistic Regression**: Accuracy = 95.61%, ROC-AUC = 0.9950
- Logistic Regression outperforms the Decision Tree baseline on this dataset.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Ahmed3li99/breast-cancer-classification-ml.git
cd breast-cancer-classification-ml
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```
