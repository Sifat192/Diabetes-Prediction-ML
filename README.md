# Diabetes Prediction using Logistic Regression

## Project Overview

This project builds a **Machine Learning classification model** to predict whether a patient has **diabetes** based on medical and lifestyle features. The model uses **Logistic Regression** to analyze patient data and estimate the probability of diabetes.

The project demonstrates a complete **machine learning workflow**, including data preprocessing, feature encoding, model training, and evaluation.

---

## Dataset

The dataset contains medical and demographic information related to diabetes risk.

**Features in the dataset:**

| Feature             | Description                                             |
| ------------------- | ------------------------------------------------------- |
| gender              | Patient gender                                          |
| age                 | Age of the patient                                      |
| hypertension        | Whether the patient has hypertension (0 = No, 1 = Yes)  |
| heart_disease       | Whether the patient has heart disease (0 = No, 1 = Yes) |
| smoking_history     | Smoking history of the patient                          |
| bmi                 | Body Mass Index                                         |
| HbA1c_level         | Average blood sugar level over the past 3 months        |
| blood_glucose_level | Current blood glucose level                             |
| diabetes            | Target variable (0 = No Diabetes, 1 = Diabetes)         |

---

## Project Workflow

The project follows these steps:

1. Importing required libraries
2. Loading and exploring the dataset
3. Data preprocessing and feature encoding
4. Splitting the dataset into training and testing sets
5. Training a **Logistic Regression model**
6. Evaluating model performance using classification metrics

---

## Technologies Used

* **Python**
* **Pandas**
* **Scikit-learn**
* **Jupyter Notebook**

---

## Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix

These metrics help assess how well the model predicts diabetes cases.

---

## Project Structure

```
Diabetes-Prediction-ML
│
├── diabetes_prediction.ipynb
├── diabetes_prediction_dataset.csv
├── README.md
└── requirements.txt
```

## Future Improvements

* Apply additional ML models (Decision Tree, Random Forest)
* Perform feature engineering
* Deploy the model using **Flask or Streamlit**

---

## Author

**Sifat Bhatia**

GitHub: https://github.com/Sifat192
LinkedIn: https://www.linkedin.com/in/sifat-bhatia-2b58b3286
