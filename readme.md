# Iris Flower Classification 🌸

This project demonstrates a **basic machine learning workflow** using the classic **Iris Flower Dataset**. It covers data loading, visualization, model training, and evaluation using **Python** and **scikit-learn**.

---

## 📌 Project Overview

The goal of this project is to classify iris flowers into one of three species:
- **Setosa**
- **Versicolor**
- **Virginica**

based on four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

A **K-Nearest Neighbors (KNN)** classifier is used to train and evaluate the model.

---

## 🧰 Technologies & Libraries Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

---

## 📂 Dataset

The dataset is loaded directly from **scikit-learn** using:

```python
from sklearn.datasets import load_iris
```

It contains **150 samples** with **4 numerical features** and **3 target classes**.

---

## 🔍 Steps Performed

1. **Load Dataset** using `load_iris()`
2. **Create DataFrame** for easier data handling
3. **Data Visualization** using Seaborn pair plots
4. **Train-Test Split** (80% training, 20% testing)
5. **Model Training** using KNN (`k = 3`)
6. **Model Evaluation**
   - Accuracy Score
   - Classification Report
   - Confusion Matrix (heatmap)

---

## 📊 Visualization Example

The project includes a **pairplot** to visualize relationships between features across different species.

---

## ✅ Results

- The KNN model achieves **high accuracy** on the test dataset.
- Performance is evaluated using precision, recall, F1-score, and confusion matrix.

---

✨ *If you found this helpful, feel free to star the repository!*

