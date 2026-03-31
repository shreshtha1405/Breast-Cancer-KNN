# 🧠 Breast Cancer Prediction using KNN

## 📌 Project Overview

This project aims to predict whether a tumor is **malignant (M)** or **benign (B)** using the **K-Nearest Neighbors (KNN)** algorithm.
It demonstrates a complete Machine Learning workflow including data preprocessing, feature scaling, model training, and evaluation.

---

## 📊 Dataset

* Breast Cancer Dataset
* Target Variable: `diagnosis`

  * **M** → Malignant (Cancerous)
  * **B** → Benign (Non-cancerous)

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🚀 Workflow

1. Data Cleaning & Preprocessing
2. Feature Selection
3. Train-Test Split (80-20)
4. Feature Scaling using StandardScaler
5. Model Training using KNN
6. Model Evaluation

---

## 📈 Model Performance

* **Accuracy:** 96%

### Classification Report:

* **Benign (B):**

  * Precision: 0.96
  * Recall: 0.97

* **Malignant (M):**

  * Precision: 0.95
  * Recall: 0.93

---

## 🔍 Key Insights

* The model performs well for both classes.
* High precision and recall indicate strong prediction capability.
* Slightly lower recall for malignant cases suggests that a few cancer cases are misclassified.

---

## 🧠 Conclusion

The KNN model achieves strong performance on the dataset with **96% accuracy**.
Feature scaling played a crucial role in improving the model’s performance.

However, in real-world medical applications, improving **recall for malignant cases** is important to minimize the risk of missing cancer diagnoses.

---

## 📌 Key Learnings

* Importance of train-test split
* Avoiding data leakage
* Role of feature scaling
* Understanding classification metrics (precision, recall, F1-score)

---

## 📁 Project Structure

```
📦 Breast-Cancer-KNN
 ┣ 📜 Breast Cancer Prediction using KNN.ipynb
 ┗ 📜 README.md
```

---

## ⭐ Future Improvements

* Hyperparameter tuning (optimal value of K)
* Try other models (Logistic Regression, SVM)
* Improve recall for malignant class
* Add cross-validation

---

## 🙌 Author

Shreshtha Sharma

