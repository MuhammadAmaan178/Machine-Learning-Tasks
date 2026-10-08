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
├── Lab_02/
│   └── Lab_02.ipynb      # Simple & Multivariate Linear Regression
│
├── Lab_03/
│   └── Lab_03.ipynb      # Logistic Regression (Breast Cancer Dataset)
│
├── Lab_04/
│   └── Lab_04.ipynb      # Decision Tree Classification & Hyperparameter Tuning (Iris Dataset)
│
├── Lab_05/
│   └── Lab_05.ipynb      # Ensemble Learning: Random Forest vs. Decision Tree (Breast Cancer Dataset)
│
├── Lab_06/
│   └── Lab-06.ipynb      # Support Vector Machines (SVM) & Hyperparameter Tuning (Titanic Dataset)
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

### 📌 Lab 02: Simple & Multivariate Linear Regression
* **Notebook**: [`Lab_02/Lab_02.ipynb`](./Lab_02/Lab_02.ipynb)
* **Key Tasks Completed**:
  - **Exploratory Data Analysis**: Visualized feature correlations using Seaborn heatmaps and pairplots.
  - **Simple Linear Regression**: Built single-variable linear regression model to predict continuous targets.
  - **Multivariate Linear Regression**: Trained multi-feature linear regression model using Scikit-Learn.
  - **Model Evaluation & Residual Analysis**: Analyzed model performance using R² score, Root Mean Squared Error (RMSE), and residual distribution plots.

### 📌 Lab 03: Logistic Regression & Binary Classification
* **Notebook**: [`Lab_03/Lab_03.ipynb`](./Lab_03/Lab_03.ipynb)
* **Dataset**: Breast Cancer Wisconsin Dataset (`sklearn.datasets`)
* **Key Tasks Completed**:
  - **Exploratory Analysis**: Visualized class distribution with count plots and feature distributions with histograms.
  - **Feature Scaling**: Standardized features using `StandardScaler`.
  - **Logistic Regression**: Trained binary classification model on scaled features.
  - **Performance Metrics**: Evaluated classification performance using Accuracy, Precision, Recall, and F1-Score.

### 📌 Lab 04: Decision Tree Classification & Hyperparameter Tuning
* **Notebook**: [`Lab_04/Lab_04.ipynb`](./Lab_04/Lab_04.ipynb)
* **Dataset**: Iris Dataset (`sklearn.datasets`)
* **Key Tasks Completed**:
  - **Exploratory Analysis**: Analyzed feature relationships with pairplots and correlation heatmaps.
  - **Decision Tree Classifier**: Built baseline `DecisionTreeClassifier`.
  - **Splitting Criteria Comparison**: Compared Gini Impurity vs. Entropy criteria.
  - **Hyperparameter Pruning**: Tuned parameters (`max_depth`, `min_samples_split`) to mitigate overfitting.
  - **Model Evaluation**: Visualized performance with Confusion Matrix heatmaps and Classification Reports.

### 📌 Lab 05: Ensemble Learning – Random Forest vs. Decision Tree
* **Notebook**: [`Lab_05/Lab_05.ipynb`](./Lab_05/Lab_05.ipynb)
* **Dataset**: Breast Cancer Dataset (`sklearn.datasets`)
* **Key Tasks Completed**:
  - **Ensemble Classifier**: Implemented `RandomForestClassifier` for robust classification.
  - **Comparative Analysis**: Trained single `DecisionTreeClassifier` on the same split for direct comparison.
  - **Evaluation & Visualization**: Compared models across Accuracy, Precision, Recall, and F1-Score; rendered heatmaps for confusion matrices.

### 📌 Lab 06: Support Vector Machines (SVM) & Hyperparameter Tuning
* **Notebook**: [`Lab_06/Lab-06.ipynb`](./Lab_06/Lab-06.ipynb)
* **Dataset**: Titanic Dataset (`seaborn`)
* **Key Tasks Completed**:
  - **Feature Preprocessing**: Cleaned data, handled missing values, selected key features (`pclass`, `sex`, `age`, `sibsp`, `parch`, `fare`, `embarked`), and applied `StandardScaler`.
  - **Support Vector Classifier (SVC)**: Built SVM classification model.
  - **Hyperparameter Optimization**: Conducted `GridSearchCV` cross-validation to select optimal hyperparameters.
  - **Model Evaluation**: Evaluated tuned model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix heatmaps.

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
