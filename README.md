# K-Nearest Neighbors on Iris Dataset 🌸

## 📘 Overview

This project applies the **K-Nearest Neighbors (KNN)** algorithm on the famous **Iris dataset** to classify flower species based on features such as sepal and petal measurements. The project includes:

- Data preprocessing  
- Label encoding  
- Standardization  
- KNN modeling with multiple `k` values  
- Accuracy and confusion matrix reporting  
- Decision boundary visualization using first two features

---

## 📁 Files

- `iris.csv` – Dataset with measurements and species labels  
- `knn_iris.py` – Python script containing the KNN classification and visualization logic  
- `iris_knn_decision_boundary.png` – Output image (optional, can be saved if needed)  

---

## 📊 Dataset Description

| Feature         | Description                  |
|-----------------|------------------------------|
| Id              | Row index (removed in script)|
| SepalLengthCm   | Sepal length in centimeters  |
| SepalWidthCm    | Sepal width in centimeters   |
| PetalLengthCm   | Petal length in centimeters  |
| PetalWidthCm    | Petal width in centimeters   |
| Species         | Iris-setosa, versicolor, or virginica |

---

## 🚀 How to Run

1. Clone or download this repo.  
2. Ensure you have Python installed (Python 3.6+ recommended).  
3. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
