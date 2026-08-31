# Machine Learning Tasks 🤖📊

Welcome to the **Machine Learning Tasks** repository! This repository contains a collection of lab tasks, data preprocessing workflows, exploratory data analysis (EDA), and machine learning model implementations completed for Semester 5 Machine Learning Lab.

---

## 📁 Repository Structure

```
Machine-Learning-Tasks/
│
├── Lab_01/
│   └── Lab_01.ipynb      # Data Preprocessing, Cleaning & Scaling (Titanic Dataset)
│
├── ML-Lab-Manual.pdf     # Official Course Lab Manual & Task Guidelines
├── .gitignore            # Git exclusion settings
└── README.md             # Project documentation
```

---

## 🧪 Labs Summary

### 📌 Lab 01: Data Preprocessing & Feature Engineering
* **Notebook**: [`Lab_01/Lab_01.ipynb`](./Lab_01/Lab_01.ipynb)
* **Dataset**: Titanic Dataset (`seaborn`)
* **Key Tasks Completed**:
  - **Data Loading & Inspection**: Inspected dataset structure using Pandas and Seaborn.
  - **Handling Missing Values**: Imputed missing age values with mean imputation (`fillna()`) and dropped rows with missing embarkation values (`dropna()`).
  - **Categorical Feature Encoding**:
    - Binary mapping for `sex` feature (`male: 0`, `female: 1`).
    - One-Hot Encoding for multi-class categorical features (`embarked`) via `pd.get_dummies()`.
  - **Feature Scaling**: Applied `StandardScaler` to normalize continuous features (`age`, `fare`, `sex`, `pclass`).
  - **Dataset Splitting**: Split data into training and testing sets (70% train, 30% test) using `train_test_split`.

---

## 🛠️ Prerequisites & Setup

To run the Jupyter notebooks locally, make sure you have Python 3 installed along with the required libraries.

### 1. Install Dependencies
```bash
pip install pandas numpy seaborn scikit-learn jupyterlab
```

### 2. Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 👤 Author

* **Muhammad Amaan** - [@MuhammadAmaan178](https://github.com/MuhammadAmaan178)
