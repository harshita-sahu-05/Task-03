# 🏠 House Price Prediction (Task-3)

## 📌 Overview

This project enhances a house price prediction system by focusing on **model reliability, generalization, and performance optimization**. It uses the California Housing Dataset and applies professional machine learning techniques such as cross-validation and hyperparameter tuning.

---

## 🎯 Objectives

* Detect overfitting and underfitting
* Apply cross-validation for reliable evaluation
* Perform hyperparameter tuning using GridSearchCV
* Improve model generalization
* Select the best-performing model

---

## 📊 Dataset

* **Name:** California Housing Dataset
* **Target:** HousePrice (Median House Value)
* **Features:**
  longitude, latitude, housing_median_age, total_rooms, total_bedrooms,
  population, households, median_income
* **Note:** `ocean_proximity` removed for simplicity

---

## 🛠️ Tech Stack

* Python
* pandas, NumPy
* scikit-learn
* matplotlib

---

## ⚙️ Workflow

1. Data Loading & Cleaning
2. Missing Value Handling
3. Feature Scaling
4. Train-Test Split
5. Model Training
6. Overfitting Analysis
7. Cross-Validation
8. Hyperparameter Tuning
9. Model Evaluation
10. Model Comparison

---

## 🤖 Models Used

* Linear Regression
* Ridge Regression
* Decision Tree Regressor (Tuned)

---

## 📈 Evaluation Metrics

* RMSE (Root Mean Squared Error)
* R² Score

---

## 📊 Results

| Model                   | RMSE       | R² Score  |
| ----------------------- | ---------- | --------- |
| Linear Regression       | ~71084     | ~0.61     |
| Ridge Regression        | ~71080     | ~0.61     |
| **Tuned Decision Tree** | **~62409** | **~0.70** |

---

## 🔍 Key Insights

* Initial Decision Tree showed overfitting (low train error, high test error)
* Cross-validation provided stable performance estimation
* Hyperparameter tuning reduced overfitting
* Tuned Decision Tree achieved best results

---

## ✅ Conclusion

The **Tuned Decision Tree** is selected as the final model due to:

* Lower RMSE
* Higher R² score
* Improved generalization

---

## 🚀 How to Run

```bash
git clone <your-repo-link>
cd <repo-folder>
```

Open the notebook and run all cells.

---

## 👨‍💻 Author

**Rudra Rajeev**
B.Tech – Saharsa College of Engineering
