# KNN-Forge: Custom k-Fold Evaluation of K-Nearest Neighbors 🔍

This project implements the **K-Nearest Neighbors (KNN)** classification algorithm from scratch and evaluates its performance using **custom k-fold cross-validation**. The results are further validated using **paired t-tests** to assess statistical significance between different values of `k`.

## 🎯 Objectives
- Understand and implement the KNN algorithm
- Split data manually into k folds without using scikit-learn's built-in cross-validation
- Measure classification performance metrics for various `k` values
- Use paired t-tests to compare classifiers

## 🛠️ Tools & Libraries
- Python
- NumPy, Pandas
- Scikit-learn (`KNeighborsClassifier`, `StandardScaler`)
- SciPy (`ttest_rel`)
- `ucimlrepo` (for dataset loading from UCI)

## 📈 Key Features
- Manual k-fold cross-validation
- Label encoding and feature scaling
- Accuracy tracking across folds
- Paired t-test for performance comparison between different values of `k`
- Modular and clean code for educational use

## 📦 Dataset
The dataset is fetched from the UCI Machine Learning Repository using the `ucimlrepo` package. You can replace it with any tabular classification dataset.

