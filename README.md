# Iris Flower Classification 🌸

A Machine Learning project built using Python and Scikit-Learn to classify Iris flower species based on their physical measurements. This project is completed as part of **Task 1: Iris Flower Classification**.

## 📌 Project Overview
The goal of this project is to train a machine learning model that can accurately predict the species of an Iris flower (*Setosa*, *Versicolor*, or *Virginica*) using four features:
* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

## 📊 Dataset
The project uses the classic `Iris.csv` dataset, which contains 150 samples of Iris flowers.
* **Source:** Included in the repository (`Iris.csv`).
* **Features:** `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`
* **Target:** `Species`

## 🚀 Features & Workflow
1. **Data Exploration & Cleaning:** Dropped unnecessary identifier columns (`Id`) and verified class distributions.
2. **Feature Scaling:** Applied `StandardScaler` to normalize dimensions for stable model training.
3. **Model Training:** Utilized a regularized **Logistic Regression** pipeline to classify the species.
4. **Evaluation:** Implemented a stratified split (70% Train / 30% Test) to ensure balanced evaluation metrics.

## 📈 Results & Performance
The trained model achieved an overall accuracy of **91.11%** on the test dataset. 

### Classification Report:
```text
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        15
Iris-versicolor       0.82      0.93      0.88        15
 Iris-virginica       0.92      0.80      0.86        15

       accuracy                           0.91        45
