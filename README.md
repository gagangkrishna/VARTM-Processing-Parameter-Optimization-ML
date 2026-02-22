# Optimization of Material Processing Parameters using Machine Learning (VARTM)

This project focuses on optimizing material processing parameters in the Vacuum Assisted Resin Transfer Molding (VARTM) process using Machine Learning techniques.

---

## 📌 Overview

Vacuum Assisted Resin Transfer Molding (VARTM) is widely used in manufacturing fiber-reinforced polymer composites. The mechanical properties of the final composite material depend on various processing parameters such as vacuum level, debulk time, fabric orientation, resin type, and fiber reinforcement.

This project aims to analyze the influence of these parameters and predict key mechanical properties using machine learning models.

---

## 🧠 Machine Learning Approach

A dataset was created from multiple VARTM experimental runs where different process parameters were systematically varied.

### Data Preprocessing
- Data Cleaning
- Handling Missing Values
- Feature Normalization
- Dataset Standardization

### Algorithms Used
- Linear Regression
- Decision Trees
- Random Forest Regression
- Support Vector Machines (SVM)
- Neural Networks

Dataset was split into training and testing sets in an 80:20 ratio for model evaluation.

---

## 📊 Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-Squared Score (R²)

---

## 🔍 Results

Machine learning models demonstrated strong predictive capability in estimating:

- Tensile Strength
- Young’s Modulus
- Volume Fraction
- Compressive Strength

Feature importance analysis showed that vacuum level, debulk time, and fiber orientation significantly influence mechanical properties.

---

## 📈 Visualizations

### Feature Importance (Random Forest Regression)
![Feature Importance](images/feature_importance.png)

### Residuals vs Predicted Values
![Residual Plot](images/residual_plot.png)

---

## 📄 Project Report
Full report available here:  
[Material_Processing_Optimization_Report.pdf](Material_Processing_Optimization_Report.pdf)

---

## 🧰 Tools & Libraries Used
- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
