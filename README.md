# 🌳 Decision Tree Classification with Hyperparameter Tuning

## 📌 Project Overview

This project demonstrates how to build a **Decision Tree Classifier** using **Scikit-learn** and improve its performance through **GridSearchCV** hyperparameter tuning.

The workflow covers the complete machine learning pipeline, from data preparation to model evaluation and optimization.

---

## 🎯 Objectives

* Build a Decision Tree Classification model.
* Split the dataset into training and testing sets.
* Train the model using default parameters.
* Evaluate model performance using classification metrics.
* Optimize the model using GridSearchCV.
* Compare the performance before and after hyperparameter tuning.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Workflow

### 1. Data Preparation

* Separate features (`X`) and target (`y`)
* Train-test split (80% training, 20% testing)
* Stratified sampling to preserve class distribution

### 2. Model Training

Train a Decision Tree Classifier using the default parameters.

### 3. Model Evaluation

Evaluate the model using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report

### 4. Hyperparameter Tuning

Optimize the Decision Tree using **GridSearchCV (5-fold Cross Validation)**.

Parameters searched:

* `criterion`

  * gini
  * entropy

* `max_depth`

  * 1
  * 2
  * 3
  * 4
  * 5
  * 6
  * 7
  * None

### 5. Final Evaluation

Use the best model obtained from GridSearchCV to predict the test data and compare its performance with the baseline model.

---

## 📊 Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report

---

## 📁 Repository Structure

```
Decision-Tree-Classification/
│
├── Decision_Tree_Classification.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Decision-Tree-Classification.git
```

2. Navigate to the project folder

```bash
cd Decision-Tree-Classification
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook
```

Run all cells to reproduce the results.

---

## 📚 Concepts Covered

* Supervised Learning
* Decision Tree Classification
* Train-Test Split
* Stratified Sampling
* Model Training
* Model Evaluation
* Hyperparameter Tuning
* Cross Validation
* GridSearchCV
* Classification Metrics

---

## 🚀 Future Improvements

* Feature importance visualization
* Decision tree visualization
* Confusion matrix
* ROC-AUC analysis (for binary classification)
* Comparison with Random Forest and Gradient Boosting models

---

## 📖 License

This project is intended for educational and learning purposes.
