# Insurance Purchase Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikit-learn)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project predicts whether a customer will purchase health insurance based on their **Age** and **Estimated Salary** using Machine Learning classification algorithms.

The objective is to compare multiple classification models and determine the best-performing algorithm.

---

## 🎯 Business Goal

As an Analyst in a Bank Insurance Company, the goal is to analyze customer data and predict whether a customer will purchase insurance.

The prediction is based on:

* Age
* Estimated Salary

This helps companies target potential customers more effectively.

---

## ❓ Problem Statement

The main objective is to implement and compare multiple **Machine Learning classification algorithms** to determine the best model for predicting insurance purchases.

The selected model should provide:

* High prediction accuracy
* Good generalization
* Minimal overfitting

---

## 📊 Dataset

The dataset used is the **Social Network Ads dataset**.

Features included in the dataset:

| Feature         | Description                       |
| --------------- | --------------------------------- |
| Age             | Age of the customer               |
| EstimatedSalary | Annual salary of the customer     |
| Purchased       | Target variable (0 = No, 1 = Yes) |

---

## 🤖 Machine Learning Algorithms Used

The following algorithms were implemented:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Algorithm Comparison
8. Prediction and Visualization

---

## 📈 Model Accuracy Comparison

| Algorithm           | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~82%     |
| KNN                 | ~84%     |
| SVM                 | ~88%     |
| Decision Tree       | ~83%     |
| Random Forest       | ~90%     |

Best Performing Model: **Random Forest**

---

## 📉 Graphical Analysis

Visualization of **Age vs Estimated Salary vs Purchase decision** helps identify patterns in customer behavior.

---

## 🔍 Predictions

Example predictions made by the trained model:

* Age 30, Salary 87,000
* Age 40, Salary 100,000
* Age 18, No Salary
* Age 35, Salary 2,500,000

---

## 💡 Insights

From the analysis:

* Customers with **higher salaries are more likely to purchase insurance**
* **Middle-aged customers** show higher purchasing probability
* Salary has a **stronger influence than age**

---

## ▶️ How to Run

Install dependencies:

```
pip install -r requirements.txt
```

Run the project:

```
python insurance_prediction.py
```

---

## 🏁 Conclusion

This project demonstrates how Machine Learning can predict customer purchasing behavior in the insurance industry and help businesses make better data-driven decisions.

---

## 👨‍💻 Author

Sandesh Gawali
