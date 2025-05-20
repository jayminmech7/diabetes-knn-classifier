# Diabetes Prediction using k-Nearest Neighbors (kNN)

This project focuses on building and evaluating a k-Nearest Neighbors (kNN) classification model to predict diabetes occurrence using the Pima Indian Diabetes dataset. The goal is to understand how this distance-based algorithm performs on medical diagnosis data.

---

## 📊 Objective

To predict the likelihood of diabetes in patients based on diagnostic health measurements using the k-Nearest Neighbors (kNN) algorithm.

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KNeighborsClassifier, train_test_split, StandardScaler, accuracy_score)

---

## 📁 Dataset

- **Source:** [Kaggle - Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Observations:** 768 samples
- **Features:** 8 numeric health indicators (e.g., Glucose, BMI, Age)
- **Target:** `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

## 🧪 Methodology

1. Data Cleaning and Standardization
2. Train-Test Split (70% train / 30% test)
3. Feature Scaling using StandardScaler
4. Model Training with `k = 5` neighbors
5. Performance Evaluation (Accuracy, Confusion Matrix)

---

## 📈 Results

- kNN model accuracy: **~X%** *(replace with actual)*
- Confusion matrix and classification report were generated
- Model performance depends heavily on `k` and feature scaling

---

## ✅ Conclusion

- The kNN model provides a solid baseline for classification tasks in medical datasets.
- The performance is sensitive to scaling and choice of `k`, making tuning crucial.
- Future enhancements could include automated hyperparameter tuning and comparison with other classification models like SVM or Random Forest.

---

## 📎 Author

**Jaymin Patel**  
[GitHub Portfolio](https://jayminmech7.github.io)
