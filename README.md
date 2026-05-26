# Iris Flower Classification 🌸

A machine learning project that classifies Iris flower species using multiple classification algorithms including Logistic Regression, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes.

---

## 📌 Project Overview

This project uses the famous Iris dataset to train and evaluate machine learning models for flower species classification.

The dataset contains measurements of iris flowers such as:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable is the flower species:
- Setosa
- Versicolor
- Virginica

---

## 🚀 Algorithms Used

### 1. Logistic Regression
A linear classification algorithm used for multiclass classification.

### 2. K-Nearest Neighbors (KNN)
Classifies data points based on the nearest neighbors.

### 3. Gaussian Naive Bayes
Probabilistic classification algorithm based on Bayes Theorem.

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Project Structure

```bash
Model_ON_IRIS_DataSet/
│
├── iris_flower.ipynb
├── iris.csv
└── README.md
```

---

## ⚙️ Workflow

### 1. Load Dataset

```python
df = pd.read_csv("iris.csv")
```

### 2. Data Preprocessing
- Checked null values
- Encoded target labels
- Prepared features and target variables

### 3. Train-Test Split

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.5, random_state=42
)
```

### 4. Model Training

The following models were trained:
- Logistic Regression
- KNN Classifier
- Gaussian Naive Bayes

### 5. Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📊 Evaluation Metrics

The project evaluates model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ▶️ How to Run

### Clone Repository

```bash
git clone git@github.com:Ashu745/Model_ON_IRIS_DataSet.git
```

### Move to Project Directory

```bash
cd Model_ON_IRIS_DataSet
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
iris_flower.ipynb
```

---

## 📷 Sample Output

The notebook displays:
- Accuracy of each model
- Confusion Matrix
- Classification Report
- Predictions on test data

---

## 🎯 Learning Outcomes

Through this project, you can learn:
- Data preprocessing
- Label Encoding
- Train-Test Splitting
- Classification algorithms
- Model evaluation techniques

---

## 📚 Dataset

Dataset used:
- Iris Flower Dataset

Sources:
- Scikit-learn Dataset Library
- UCI Machine Learning Repository

---

## 👨‍💻 Author

Created by Ashu745 🚀

GitHub: https://github.com/Ashu745
