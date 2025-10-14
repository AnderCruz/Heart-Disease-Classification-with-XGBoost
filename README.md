# Heart Disease Classification with XGBoost

This project was developed by **Nowa Analytics** as part of a consultancy case study in the medical research field. The main goal is to build a **machine learning model** using **XGBoost** to classify whether patients have heart disease or not, based on demographic data and medical examination results.

## 📌 Project Overview

A medical research group wants to create a predictive model that can classify patients into two categories:

* **Presence of heart disease**
* **Absence of heart disease**

To achieve this, we will leverage the **XGBoost library**, one of the most powerful ensemble learning techniques for structured data classification tasks.

## 🧩 Dataset Description

The dataset contains several patient features, including:

* **Age** – Patient’s age
* **Sex** – Biological sex (1 = male, 0 = female)
* **Chest Pain Type (1–4)** – Scale indicating chest pain type
* **Resting Blood Pressure** – Measured in mm Hg
* **Cholesterol** – Serum cholesterol level
* **Fasting Blood Sugar > 120 mg/dl** (1 = true, 0 = false)
* **Resting Electrocardiogram (ECG) Results** – Numeric values
* **Max Heart Rate Achieved** – Measured during exercise
* **Exercise-Induced Angina** (1 = yes, 0 = no)
* **ST Depression (Oldpeak)** – Depression induced by exercise relative to rest
* **ST Slope** – The slope of the peak exercise ST segment
* **Number of Major Vessels Colored by Fluoroscopy** – Numeric values
* **Thalassemia Test Results** – Numeric values

**Target variable:**

* **Heart Disease** → `Presence` or `Absence`

## 🎯 Objectives

* Apply **XGBoost** for **binary classification**
* Perform **model evaluation** using classification metrics (Accuracy, Precision, Recall, F1-Score, AUC)
* Use **cross-validation** to validate model performance
* Analyze the impact of **number of boosting rounds**
* Optimize the model through **hyperparameter tuning**
* Integrate XGBoost into **machine learning pipelines**

## ⚙️ Technologies Used

* **Python 3.10+**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Preprocessing, metrics, and pipelines
* **XGBoost** – Gradient boosting classification

## 📂 Project Structure

```
📦 heart-disease-xgboost
 ┣ 📂 data            # Dataset files
 ┣ 📂 notebooks       # Jupyter notebooks for analysis
 ┣ 📂 src             # Source code with pipeline implementation
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📜 LICENSE
```

## 📊 Expected Outcomes

* Build a robust **binary classification model** for heart disease prediction.
* Identify key medical and demographic **features that impact predictions**.
* Provide a foundation for future deployment in **healthcare decision support systems**.



🔹 Developed by **Nowa Analytics** | Data Science & AI Consultancy

