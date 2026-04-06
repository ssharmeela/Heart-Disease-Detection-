# ❤️ Heart Disease Detection using Random Forest

## 📌 Project Overview

This project predicts whether a person has heart disease using a **Machine Learning model (Random Forest Classifier)**.
The dataset is **synthetically generated** using NumPy to simulate real-world medical data.

---

## 🎯 Objective

To build a classification model that:

* Predicts heart disease (0 = No, 1 = Yes)
* Evaluates performance using accuracy and confusion matrix
* Provides user-based prediction

---

## 🧠 Technologies Used

* Python 🐍
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

---

## 📊 Dataset Description

The dataset is generated programmatically with 500 samples.

### Features:

* `age` – Age of patient
* `gender` – 0 = Female, 1 = Male
* `chest_pain` – Type (0–3)
* `blood_pressure` – Resting BP
* `cholesterol` – Cholesterol level
* `blood_sugar` – 0 = Normal, 1 = High
* `max_heart_rate` – Maximum heart rate
* `exercise_angina` – 0 = No, 1 = Yes

### Target:

* `heart_disease`

  * 0 → No disease
  * 1 → Disease

---

## ⚙️ How It Works

1. Generate dataset using NumPy
2. Create target column based on medical conditions
3. Split data into training and testing sets
4. Train model using Random Forest
5. Predict results
6. Evaluate using:

   * Accuracy
   * Classification Report
   * Confusion Matrix
7. Take user input for prediction

---

## 🌳 Random Forest Explained

Random Forest is an ensemble learning method that:

* Uses multiple decision trees
* Combines predictions using majority voting
* Reduces overfitting and improves accuracy

---

## 📈 Evaluation Metrics

### ✅ Accuracy

Measures overall correctness of the model.

### 📊 Confusion Matrix

Shows:

* True Positive (TP)
* True Negative (TN)
* False Positive (FP)
* False Negative (FN)

⚠️ In medical applications, **False Negatives are critical** because they miss actual patients.

---

## ▶️ How to Run the Project

```bash
# Install dependencies
pip install numpy pandas scikit-learn matplotlib

# Run the Python file
python your_file_name.py
```

---

## 🧪 Sample Output

* Accuracy: ~85%–95% (depends on random data)
* Confusion Matrix visualization
* Feature importance graph

---

## 🎤 Viva Explanation (Quick Summary)

* Generated dataset using NumPy
* Used Random Forest for classification
* Evaluated using accuracy & confusion matrix
* Added user input for real-time prediction

---

## 🚀 Future Improvements

* Use real dataset (UCI/Kaggle)
* Build a web app (Flask/Streamlit)
* Improve model tuning

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to predict heart disease effectively using Random Forest, with proper evaluation techniques.

---

## 🙌 Author

**Sharmeela S**
B.Tech CSE | Aspiring Ai engineer

---

