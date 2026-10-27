# ML Studio — Interactive Machine Learning Laboratory

ML Studio is an interactive Machine Learning mini-project built using **Python, Flask, Scikit-learn, HTML, and CSS**.

The project demonstrates multiple Machine Learning algorithms using the **UCI Student Performance Dataset** through a modern and interactive web interface.

## Machine Learning Experiments

1. Dataset Understanding and Exploration
2. Simple Linear Regression
3. Multiple Linear Regression
4. Multiple Linear Regression with 3+ Features
5. Binary Logistic Regression
6. Multiclass Logistic Regression
7. Decision Tree
8. Standardization and Normalization
9. K-Nearest Neighbors (KNN)
10. Naive Bayes
11. Linear SVM
12. Non-Linear SVM
13. Random Forest

## Features

- Interactive Machine Learning dashboard
- Student Performance Dataset exploration
- Regression model evaluation using R², MSE, and MAE
- Classification model accuracy comparison
- Binary and multiclass classification
- Interactive KNN experiment with adjustable K value
- Standardization and normalization comparison
- Linear vs Non-Linear SVM comparison
- Random Forest feature importance
- Model Arena for comparing classifier performance
- Automatic identification of the best-performing model

## Dataset

The project uses the **Student Performance Dataset** from the UCI Machine Learning Repository.

The dataset contains student academic and personal attributes such as:

- Age
- Study Time
- Previous Failures
- Absences
- First Period Grade (G1)
- Second Period Grade (G2)
- Final Grade (G3)

### Targets

**Regression:**  
Predict the student's final grade `G3`.

**Binary Classification:**  
Classify students as `Pass` or `Fail`.

**Multiclass Classification:**  
Classify student performance as `Low`, `Medium`, or `High`.

## Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- UCI ML Repository
- HTML
- CSS
- JavaScript
- Pickle

## Project Structure

```text
ML-Studio-Interactive-Machine-Learning-Lab/
│
├── app.py
├── README.md
├── requirements.txt
│
├── models/
│   ├── SimpleLinearRegression.pkl
│   ├── MultipleLinearRegression.pkl
│   ├── MultipleLinearRegression3Plus.pkl
│   ├── BinaryLogisticRegression.pkl
│   ├── MulticlassLogisticRegression.pkl
│   ├── DecisionTree.pkl
│   ├── KNN.pkl
│   ├── NaiveBayes.pkl
│   ├── LinearSVM.pkl
│   ├── NonLinearSVM.pkl
│   └── RandomForest.pkl
│
└── templates/
    └── index.html
```

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Open the project folder:

```bash
cd ML-Studio-Interactive-Machine-Learning-Lab
```

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open the application in your browser:

```text
http://127.0.0.1:5000
```

## Machine Learning Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison
```

## Model Evaluation

Regression models are evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

Classification models are evaluated using:

- Accuracy
- Confusion Matrix

The **Model Arena** compares the performance of different classification algorithms and automatically highlights the best-performing model.

## Purpose

The main objective of ML Studio is to demonstrate multiple Machine Learning concepts and algorithms in a single interactive web application while providing an easy way to understand, compare, and experiment with different ML models.

---

**ML Studio — One Dataset. Every ML Experiment.**
