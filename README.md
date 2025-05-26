# 🖼️ Image Classification with SVM

A machine learning project that classifies images of **cats**, **dogs**, **horses**, and **humans** using **Support Vector Machines (SVM)** — implemented both **from scratch** and using **scikit-learn**.

---

## 🚀 Features

- 📂 Classifies images into four categories: `cat`, `dog`, `horse`, `human`
- 🧠 Custom SVM implementation (One-vs-One strategy)
- ⚡ Comparison with scikit-learn SVM
- 🔍 Voting-based multi-class prediction
- 📊 Accuracy evaluation included

---

## 🛠️ How It Works

### 1. Data Preparation
- Organize images in subfolders inside the `dataset/` directory
- Each image is resized and converted into a flattened NumPy array.
- Labels are inferred from folder names.

### 2. Preprocessing
- Images are **normalized** (pixel values scaled between 0 and 1).
- Data is **shuffled** to ensure balanced training.

### 3. Custom SVM
- Uses **One-vs-One** classification.
- A binary SVM classifier is trained for every pair of classes.
- Core optimization implemented from scratch.

### 4. Prediction & Evaluation
- Class prediction based on **voting** from classifiers.
- Final **accuracy** is calculated on test data.

### 5. Scikit-learn SVM
- Trains a **Linear SVM** using scikit-learn.
- Performance compared with the custom implementation.

---

## 📦 Requirements

- numpy
- matplotlib
- keras
- scikit-learn
