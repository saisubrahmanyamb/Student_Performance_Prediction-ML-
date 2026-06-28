# Student Performance Prediction using Machine Learning

## Overview

This project predicts students' mathematics scores using demographic and educational information. Multiple machine learning regression models are trained, evaluated, and compared to identify the best-performing model.

The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, performance evaluation, and model comparison.

---

## Objective

The objective of this project is to analyze the factors affecting students' mathematics performance and develop a machine learning model capable of predicting math scores accurately.

---

## Dataset

**Dataset Name:** Students Performance in Exams

**Source:** Kaggle

**Records:** 1000

**Features:** 8

### Dataset Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

**Target Variable**

* Math Score

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Best Model Selection
10. Save Best Model

---

## Exploratory Data Analysis

The following visualizations were generated during EDA:

* Gender Distribution
* Race/Ethnicity Distribution
* Parental Education Distribution
* Lunch Distribution
* Test Preparation Distribution
* Math Score Distribution
* Reading Score Distribution
* Writing Score Distribution
* Correlation Heatmap
* Math Score by Gender
* Math Score by Test Preparation
* Reading Score vs Writing Score

---

## Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor

---

## Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Model Comparison

All trained models were compared using:

* R² Score Comparison
* RMSE Comparison
* MAE Comparison
* Actual vs Predicted Plot
* Residual Plot
* Feature Importance (Tree-Based Models)

The model with the highest R² Score was selected as the final prediction model.

---

## Project Structure

```
ML_Project_Istudio/
│
├── data/
│   └── StudentsPerformance.csv
│
├── notebook/
│   └── Student_Performance.ipynb
│
├── graphs/
│   ├── 01_gender_distribution.png
│   ├── ...
│
├── models/
│   └── best_model.pkl
│
├── requirements.txt
│
└── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* VS Code

---

## Installation

Clone the repository:

```bash
git clone https://github.com/saisubrahmanyamb/Student_Performance_Prediction-ML-.git
```

Navigate to the project directory:

```bash
cd Student_Performance_Prediction-ML-
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebook/Student_Performance.ipynb
```

Run all the cells to reproduce the project.

## Results

The regression models were trained and compared based on multiple evaluation metrics. The model achieving the highest R² Score and the lowest prediction errors was selected as the final model for predicting student mathematics scores.

---

## Conclusion

This project demonstrates the complete implementation of a supervised machine learning regression workflow. Through data analysis, preprocessing, model training, evaluation, and comparison, the project identifies the most suitable regression model for predicting student mathematics performance.

---

**Boggarapu Sai Subrahmanyam**
