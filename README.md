# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)
---
## 📌 Overview

This project implements the K-Nearest Neighbors (KNN) classification algorithm using the famous Iris Dataset.

---
## 📊 Dataset Information

* Total Samples: 150
* Features: 4 numerical features
* Target Classes: 3 flower species
* No missing values
---
## Target Distribution:

* 50 Setosa
* 50 Versicolor
* 50 Virginica

---
## 🛠️ Technologies & Libraries Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

---
## ⚙️ Project Workflow
**1️⃣ Dataset Loading**
``` python
from sklearn.datasets import load_iris
Dataset = load_iris()
```
**2️⃣ Feature & Target Separation**

X = Dataset.data
y = Dataset.target

**3️⃣ Train-Test Split**

* 80% Training Data
* 20% Testing Data
* random_state=1

**4️⃣ Feature Scaling**
* StandardScaler
* MinMaxScaler

**5️⃣ Model Training**
```python
from sklearn.neighbors import KNeighborsClassifier
```
```
model = KNeighborsClassifier(n_neighbors=5)
model.fit(X_train, y_train)
```

**6️⃣ Prediction**
```
y_pred = model.predict(X_test)
```

**7️⃣ Model Evaluation**
Used:

* Accuracy Score
* Classification Report
* Confusion Matrix

---
## 📈 Model Performance

**✅ Accuracy Score**

Accuracy = 1.0 (100%)

---
## 📋 Classification Report
```
Class	Precision	Recall	F1-Score
Setosa	1.00	1.00	1.00
Versicolor	1.00	1.00	1.00
Virginica	1.00	1.00	1.00
```
---
## 🔲 Confusion Matrix

```
[[11  0  0]
 [ 0 13  0]
 [ 0  0  6]]
```
Perfect classification on test dataset.

---
## 📊 Visualization

**Heatmap visualization of confusion matrix using Seaborn:**

<img width="621" height="528" alt="image" src="https://github.com/user-attachments/assets/4a6c062b-b3ca-4526-bb08-026b6a0877dc" />

---
## 📂 Project Structure
KNN-Iris-Classification/
* │── KNN_Iris_Model.ipynb
* │── README.md

---
## 💡 Key Concepts Demonstrated

* Supervised Machine Learning
* Classification
* Feature Scaling
* Model Evaluation Metrics
* Confusion Matrix Visualization
* Distance-based Algorithms

---
## 🚀 Skills Demonstrated

* End-to-End ML Workflow
* Data Preprocessing
* Model Building
* Performance Evaluation
* Visualization Techniques
* Scikit-learn Implementation
---  
## 👨‍💻 Author

**Nagaraj M**

GitHub: https://github.com/M-Nagaraj02

---
