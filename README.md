# Smart Outcome Predictor

## 📌 Project Overview
This project builds a Machine Learning model to predict smart outcomes using a classification approach. The notebook covers the complete machine learning workflow, including data loading, preprocessing, feature engineering, model training, and performance evaluation.

---

## 📂 Dataset
**Dataset Name:**
Smart_Outcome_Predictor_Dataset_5200.csv

The dataset contains multiple features used to predict the target outcome.

---

## 🎯 Objective
To develop a classification model capable of predicting the target outcome based on the given input features.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

Machine Learning Libraries:

- LabelEncoder
- SimpleImputer
- StandardScaler
- train_test_split
- LogisticRegression
- DecisionTreeClassifier
- accuracy_score

---

## 🔄 Project Workflow

### 1. Import Libraries
Imported all required Python libraries for data manipulation, visualization, and machine learning.

### 2. Load Dataset
Loaded the Smart Outcome Predictor dataset into a Pandas DataFrame.

### 3. Data Exploration
Performed:
- Dataset shape
- First five records
- Dataset information
- Statistical summary

### 4. Data Preprocessing
- Checked missing values
- Handled missing values using SimpleImputer
- Encoded categorical variables using LabelEncoder
- Standardized numerical features using StandardScaler

### 5. Feature Selection
Separated:
- Independent Variables (X)
- Target Variable (y)

### 6. Train-Test Split
Split the dataset into:
- Training Set
- Testing Set

### 7. Model Building
Implemented the following Machine Learning models:

- Logistic Regression
- Decision Tree Classifier

### 8. Model Evaluation
Evaluated the model using:

- Accuracy Score

---

## 📊 Output
The notebook compares the performance of classification models and predicts the target outcome based on the processed dataset.

---

## 📈 Machine Learning Pipeline

Dataset
↓
Data Exploration
↓
Missing Value Treatment
↓
Label Encoding
↓
Feature Scaling
↓
Train-Test Split
↓
Model Training
↓
Prediction
↓
Accuracy Evaluation

---

## 📁 Files Included

- Exam5(code).ipynb
- Smart_Outcome_Predictor_Dataset_5200.csv
- README.md

---

## ✅ Conclusion
This project demonstrates an end-to-end Machine Learning classification pipeline. It includes preprocessing, feature encoding, feature scaling, model training, prediction, and evaluation using Logistic Regression and Decision Tree algorithms to predict the target outcome.

---

## 👨‍💻 Author

**Name:** Abhiraj Medhat
