# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project implements the **K-Nearest Neighbors (KNN)** algorithm to classify iris flowers into three species: **setosa**, **versicolor**, and **virginica** using the classic **Iris dataset**.

---

## 📁 Dataset

- **Source**: `sklearn.datasets.load_iris()`
- **Features**:  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target Classes**:  
  - 0 = Setosa  
  - 1 = Versicolor  
  - 2 = Virginica

---

## ✅ Project Steps

### 🔍 Step 1: Data Loading
- Loaded the Iris dataset using sklearn
- Split into features (`X`) and target (`y`)

### 🔍 Step 2: Normalization
- Used `StandardScaler` to normalize feature values
- KNN is distance-based, so scaling is important

### ✂️ Step 3: Train-Test Split
- 80% training, 20% testing
- Used `train_test_split` from sklearn

### 🤖 Step 4: KNN Model Training
- Used `KNeighborsClassifier` from sklearn
- Trained model with **K = 3**

### 📈 Step 5: Evaluation
- Printed confusion matrix and classification report
- Achieved high accuracy and balanced class prediction

### 🔁 Step 6: K-Value Tuning
- Tried `K` from 1 to 20
- Plotted **Error Rate vs K**
- Helped determine the optimal K-value

---

## 📊 Results

- **Best K Value**: 3 (initial test)
- **Accuracy**: ~96% on test set
- **Confusion Matrix & Classification Report**: Included in notebook
- **Error Rate vs K Plot**: Helps visualize model performance

---

## 📂 Files in Repo

- `Task_6.ipynb`: Main notebook with code, graph, and evaluation
- `README.md`: This file

---

## 💡 Key Learnings

- KNN is a simple yet powerful classifier
- Normalization significantly impacts KNN performance
- Choosing the right value of **K** is crucial for model accuracy
- Evaluation metrics like **confusion matrix** and **error plots** are essential

---
