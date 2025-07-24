# Breast-Cancer-Detection
Breast Cancer Detection uses machine learning models like Logistic Regression and SVM to classify tumors as benign or malignant based on clinical data. Built on Google Colab, it achieves high accuracy and aids in early cancer diagnosis.


> 📎 [Open in Google Colab](https://colab.research.google.com/drive/1dNMXnmvxqKs3h1LBIf-dIHqPP3oTye2l#scrollTo=BerRwPTdxdKa)

---

## 📌 Project Overview

- 📥 Load and explore the *Breast Cancer Wisconsin Diagnostic dataset*
- 🧹 Preprocess the data (handle missing values, feature scaling, etc.)
- 📊 Perform *Exploratory Data Analysis (EDA)* to understand patterns
- 🤖 Train classification models (e.g., Logistic Regression, Random Forest, SVM)
- 🎯 Evaluate using metrics like accuracy, confusion matrix, precision, recall
- 📈 Predict cancer diagnosis on new/unseen data

---

## 🔍 Dataset

- *Source*: Breast Cancer Wisconsin (Diagnostic) Dataset  
- *Features*: 30 real-valued input features (mean, standard error, and worst values of cell nuclei characteristics)
- *Target*: Diagnosis (M = malignant, B = benign)

---

## 🛠 Technologies Used

- *Python*
- *Google Colab*
- *Pandas* & *NumPy* for data manipulation
- *Matplotlib* & *Seaborn* for data visualization
- *Scikit-learn* for model building and evaluation

---

## 📁 Files

- breast_cancer_detection.ipynb: Colab notebook with complete code and output

---

## 🚀 How to Run

1. Click the *"Open in Colab"* button above  
2. Run all cells sequentially  
3. Upload the dataset if prompted (or use sklearn.datasets.load_breast_cancer())

---

## ✅ Results

- Achieved over *95% accuracy* with multiple classifiers
- Model performance evaluated using:
  - Confusion Matrix
  - Precision, Recall, F1-score
  - ROC-AUC Curve
