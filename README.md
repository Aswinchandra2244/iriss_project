# 🌸 Iris Flower Classification — Machine Learning Project

## 📌 Overview
This project applies supervised machine learning techniques to classify Iris flowers into three species — **Iris Setosa**, **Iris Versicolor**, and **Iris Virginica** — based on four measurable features: **sepal length**, **sepal width**, **petal length**, and **petal width**. This dataset is one of the most widely used benchmarks in Machine Learning.

---

## 🎯 Objectives

- Load and explore the Iris dataset
- Train multiple classification models
- Evaluate model performance
- Compare algorithms based on accuracy and classification metrics
- Visualize patterns and insights from the data

---

## 📂 Dataset Details

The **Iris dataset**, introduced by Ronald Fisher, contains:

| Attribute | Description |
|----------|-------------|
| Samples | 150 |
| Classes | Setosa, Versicolor, Virginica |
| Features | Sepal Length, Sepal Width, Petal Length, Petal Width |
| Format | Numeric |

Each species has **50 samples**, making this a balanced dataset.

---

## 🛠 Tech Stack

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**

---

## 🤖 Models Implemented

The following machine learning algorithms were trained and evaluated:

- Logistic Regression  
- k-Nearest Neighbors (kNN)  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)

### 🏆 Best Model
The **Support Vector Machine (SVM)** model achieved the **highest accuracy** in this project.

---

## 📊 Evaluation Metrics

The models were evaluated using standard ML metrics:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-Score)

Data visualization includes:

- Feature distribution plots
- Pairwise feature relationships
- Correlation heatmap

---

## 🚀 Workflow

```mermaid
flowchart TD
A[Load Dataset] --> B[Exploratory Data Analysis]
B --> C[Train-Test Split]
C --> D[Model Training]
D --> E[Model Evaluation]
E --> F[Model Comparison]
