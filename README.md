#  Iris Flower Classification - CodeAlpha Internship

##  Project Overview

This project is part of the **CodeAlpha Data Science Internship**.
The objective is to build a machine learning model that can classify iris flowers into three species based on their physical measurements.

---

## Objective

The goal of this project is to classify iris flowers into three categories:

* Setosa
* Versicolor
* Virginica

using features such as:

* Sepal length
* Sepal width
* Petal length
* Petal width

---

## Dataset

The dataset used is the **Iris dataset**, available directly from Scikit-learn.

* Total samples: 150
* Features: 4
* Classes: 3

---

##  Steps Performed

### 1. Data Loading

The dataset was loaded using Scikit-learn.

### 2. Exploratory Data Analysis (EDA)

* Visualization using pairplots
* Identification of feature relationships
* Observation: Petal features are the most discriminative

### 3. Data Splitting

* Training set: 80%
* Testing set: 20%

### 4. Model Building

* Algorithm used: **K-Nearest Neighbors (KNN)**

### 5. Model Evaluation

* Accuracy score
* Classification report
* Confusion matrix

### 6. Model Optimization

* Cross-validation was used to test multiple values of K
* Best performance achieved with K = 6, 7, and 10

---

## Results

* **Best Accuracy (Test Set):** 1.00
* **Cross-Validation Accuracy:** ~0.98

### Confusion Matrix:

```
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
```

### Interpretation:

* The model perfectly classified all test samples
* High consistency confirmed with cross-validation

---

## Key Insights

* The dataset is well-structured and easy to classify
* The species *Setosa* is completely separable
* *Versicolor* and *Virginica* show slight overlap
* **Petal length and petal width are the most important features**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Structure

```
CodeAlpha_Iris_Classification/
│
├── iris_classification.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/CodeAlpha_Iris_Classification.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open the notebook:

```
jupyter notebook iris_classification.ipynb
```

---

## Internship Requirement

This project fulfills the mandatory **Task 1: Iris Flower Classification** required for the CodeAlpha internship.

---

## Author

**Codjo Ulrich Expéra AKAKPO**
Data Science Intern - CodeAlpha

---
* Machine learning
* Model evaluation
