# 🌸 Iris Flower Classification using KNN Pipeline

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)](https://scikit-learn.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF.svg)](https://www.kaggle.com/code/muhammadfarhanmrs/iris-classification-knn-pipeline-ipynb/notebook)

An end-to-end Machine Learning project demonstrating data preprocessing, feature scaling, and classification using the **K-Nearest Neighbors (KNN)** algorithm wrapped inside a Scikit-Learn **Pipeline**. 

> **Project Context:** This repository represents my **2nd Machine Learning Project** as an **AI Intern at DecodeLab**.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset Details](#-dataset-details)
- [Pipeline Architecture](#-pipeline-architecture)
- [Installation & Setup](#-installation--setup)
- [Results & Evaluation](#-results--evaluation)
- [Repository Structure](#-repository-structure)
- [Author & Acknowledgments](#-author--acknowledgments)
- [License](#-license)

---

## 📌 Project Overview

The primary objective of this project is to build a robust classification workflow for predicting the species of the Iris flower based on its morphological measurements. By incorporating Scikit-Learn's `Pipeline`, the workflow prevents data leakage during cross-validation and feature scaling, ensuring clean and reproducible code execution.

---

## 📊 Dataset Details

The **Iris Dataset** consists of 150 samples across 3 classes:
- **Features:**
  1. `Sepal Length` (cm)
  2. `Sepal Width` (cm)
  3. `Petal Length` (cm)
  4. `Petal Width` (cm)
- **Target Classes:**
  - `Iris-setosa`
  - `Iris-versicolor`
  - `Iris-virginica`

---

## ⚙️ Pipeline Architecture

The machine learning pipeline consists of two main components:
1. **Feature Scaling (`StandardScaler`):** Standardizes numerical features by removing the mean and scaling to unit variance (essential for distance-based algorithms like KNN).
2. **Classification (`KNeighborsClassifier`):** Classifies instances based on majority vote of nearest neighbors in the feature space.

```text
Raw Data ➔ Train/Test Split ➔ StandardScaler ➔ KNeighborsClassifier ➔ Prediction & Evaluation
```

---

## 🚀 Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Farhanillahiclass/Iris-Classification-using-KNN-Pipeline.git
   cd Iris-Classification-using-KNN-Pipeline
   ```

2. **Set Up Virtual Environment (Optional but Recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

4. **Launch Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 📈 Results & Evaluation

The model performance is evaluated using standard metrics:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-Score)**

---

## 📁 Repository Structure

```text
.
├── iris-classification-knn-pipeline.ipynb   # Main Jupyter Notebook
├── README.md                                # Project Documentation
└── LICENSE                                  # MIT License
```

---

## 👨‍💻 Author & Acknowledgments

- **Muhammad Farhan**
- **Role:** AI Intern at DecodeLab
- **Kaggle Profile:** [@muhammadfarhanmrs](https://www.kaggle.com/muhammadfarhanmrs)
- **GitHub Profile:** [@muhammadfarhanmrs](https://github.com/muhammadfarhanmrs)

Special thanks to **DecodeLab** for guiding this learning experience.

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
