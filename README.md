# 🌸 Iris Flower Classification

## 📌 Project Overview
This project aims to classify Iris flower species using Machine Learning algorithms.  
Based on flower measurements, the model predicts the correct species.

---

## 📊 Dataset Information
The dataset contains 150 samples with the following features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  
- Species (Target Variable)

There are 3 classes:
- Setosa  
- Versicolor  
- Virginica  

---

## 🔎 Exploratory Data Analysis (EDA)

The following steps were performed:

- Checked dataset shape and structure  
- Displayed summary statistics  
- Verified class distribution  
- Visualized feature relationships using:
  - Pairplot  
  - Correlation Heatmap  

### Key Observations:
- Petal length and petal width have strong positive correlation.
- Setosa class is clearly separable from other classes.
- Some overlap exists between Versicolor and Virginica.

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Train/Test split: 80% / 20%
- Model trained using Scikit-learn
- Accuracy evaluated on test data

### 2️⃣ Decision Tree Classifier
- Trained using default parameters
- Compared with Logistic Regression

---

## 📈 Model Evaluation

- Accuracy comparison between models
- Confusion matrices plotted

## 📊 Confusion Matrix - Logistic Regression

![Logistic CM](images/confusion_matrix_logistic.png)

## 📊 Confusion Matrix - Decision Tree

![Decision Tree CM](images/confusion_matrix_tree.png)

### Interpretation:
- Setosa was classified with nearly 100% accuracy.
- Most misclassifications occurred between Versicolor and Virginica.
- Logistic Regression showed strong generalization performance.

---

## 🔮 Prediction Example

Example input:[5.1, 3.5, 1.4, 0.2]

Predicted Output:
Setosa

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📌 Conclusion

Both Logistic Regression and Decision Tree models performed well on the Iris dataset.  
The project successfully demonstrates:

- Data Exploration  
- Data Visualization  
- Model Training  
- Model Evaluation  
- Prediction  

