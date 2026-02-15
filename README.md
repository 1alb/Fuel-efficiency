# 🚗 Fuel Efficiency Prediction using Machine Learning

## 📌 Project Overview

This project predicts **vehicle fuel efficiency** using machine learning techniques.
The model analyzes vehicle specifications such as manufacturer, vehicle type, driving efficiency, and range to estimate combined fuel efficiency.

This system helps understand energy consumption patterns and supports eco-friendly transportation analysis.

---

## 🎯 Objectives

* Predict combined fuel efficiency of vehicles
* Clean and preprocess real-world dataset
* Handle missing and mixed-format data
* Evaluate model performance using error metrics
* Visualize predictions for better understanding

---

## 📂 Dataset Information

The dataset contains Korean vehicle efficiency data with the following attributes:

| Column   | Description                           |
| -------- | ------------------------------------- |
| 모델명      | Vehicle Model                         |
| 제조(수입사)  | Manufacturer                          |
| 차종       | Vehicle Type                          |
| 유형       | Usage Type                            |
| 복합_연비    | **Combined Fuel Efficiency (Target)** |
| 1회충전주행거리 | Range per charge                      |
| 도심_연비    | City efficiency                       |
| 고속도로_연비  | Highway efficiency                    |
| 등급       | Vehicle class                         |

**Target Variable:** `복합_연비` (Combined Fuel Efficiency)

---

## 🧹 Data Preprocessing

The dataset required several preprocessing steps:

✔ Removed empty columns
✔ Handled missing values using imputation
✔ Converted mixed values like `"2.9 / 10.7"` into numeric form
✔ Encoded categorical features
✔ Standardized numerical features

---

## 🤖 Machine Learning Models Used

### 🌲 Random Forest Regressor

* Ensemble learning method
* Handles nonlinear relationships
* High accuracy and robustness

### 🌳 Extra Trees Regressor

* Faster variant of Random Forest
* Reduces variance
* Improvers prediction stability

---

## 📊 Model Evaluation Metrics

The model performance was evaluated using:

* **MSE (Mean Squared Error)** – penalizes large errors
* **RMSE (Root Mean Squared Error)** – error in efficiency units
* **MAE (Mean Absolute Error)** – average prediction error
* **R² Score** – model accuracy strength
* **MAPE** – percentage error
* **Accuracy (%)** = 100 − MAPE

---

## 📈 Visualization

Scatter plots compare:

**Actual vs Predicted Fuel Efficiency**

✔ Points near the diagonal line indicate accurate predictions.
✔ Deviations show prediction errors.

---

## 🧠 Results

The machine learning models successfully predicted fuel efficiency with high accuracy.

Typical performance:

* Low RMSE & MAE
* High R² score
* Prediction accuracy above **90%**

---

## 💡 Key Insights

* Vehicle efficiency is influenced by usage type and range.
* City and highway efficiency strongly impact combined efficiency.
* Proper data preprocessing significantly improves accuracy.

---

## ⚙️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib

---

## ▶️ How to Run the Project

1️⃣ Upload dataset to Google Colab or project folder

2️⃣ Install dependencies (if needed):

```bash
pip install pandas scikit-learn matplotlib
```

3️⃣ Run the Python script.

---

## 🚀 Future Improvements

* Add deep learning models
* Build a web dashboard for predictions
* Deploy as a real-time API
* Include more global fuel datasets

---

## 👩‍💻 Author

**Monisha Gaur**

---

## 📚 References

* Scikit-learn Documentation
* Fuel efficiency research datasets
* Machine learning regression techniques

---

⭐ If you found this project useful, consider giving it a star!
