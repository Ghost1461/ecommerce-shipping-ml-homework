# E-Commerce Shipping Delivery Prediction Using Machine Learning

## Project Overview

This project is developed as part of the **CME 4403 Machine Learning** course.

The main objective is to predict whether an e-commerce shipment will be delivered on time using different machine learning classification algorithms.

The project focuses on comparing multiple classification models, evaluating their performance, and investigating the effects of hyperparameter tuning.

## Dataset

**Dataset:** E-Commerce Shipping Data

**Source:** [Kaggle – E-Commerce Shipping Data](https://www.kaggle.com/datasets/prachi13/customer-analytics)

The dataset contains **10,999 records** describing e-commerce shipments and their associated characteristics.

Some of the features include:

- Warehouse block
- Mode of shipment
- Customer care calls
- Customer rating
- Product cost
- Prior purchases
- Product importance
- Discount offered
- Product weight

**Target Variable:** `Reached.on.Time_Y.N`

- `0`: Delivered on time
- `1`: Not delivered on time

## Machine Learning Models

The following classification algorithms will be implemented and compared:

1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Logistic Regression**
4. **Random Forest Classifier**

## Methodology

The planned workflow consists of:

1. **Exploratory Data Analysis (EDA)**

   - Dataset inspection
   - Missing value analysis
   - Feature distributions
   - Class distribution analysis
2. **Data Preprocessing**

   - Handling missing values
   - Encoding categorical features
   - Feature scaling where necessary
   - Train-test splitting
3. **Model Training**

   - Training four classification algorithms
   - Applying cross-validation
   - Hyperparameter tuning
4. **Model Evaluation**

   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC
   - Confusion Matrix
5. **Model Comparison**

   - Comparing classification performance
   - Analyzing hyperparameter effects
   - Discussing the strengths and limitations of each algorithm

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Structure

```Shell
ecommerce-shipping-ml/
│
├── data_preprocessing.py
├── knn.py
├── decision_tree.py
├── logistic_regression.py
├── random_forest.py
├── model_comparison.py
│
├── README.md
├── .gitignore
└── Train.csv
```

The structure represents the planned project organization. Some files will be added during development.

## Expected Outcome

The project aims to evaluate and compare different machine learning algorithms on the same shipping dataset.

Cross-validation and hyperparameter tuning will be used to support a fair model comparison. The final results will be presented through performance tables and visualizations.

## Course Information

**Course:** CME 4403 – Machine Learning

**Department:** Computer Engineering

**University:** Dokuz Eylül University

**Academic Year:** 2026–2027

## References

- [E-Commerce Shipping Dataset – Kaggle](https://www.kaggle.com/datasets/prachi13/customer-analytics)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
