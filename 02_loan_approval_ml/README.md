# 🏦 Loan Approval Prediction (Machine Learning)

## 📌 Project Overview

This project predicts whether a loan application will be **approved or not approved** using a **Logistic Regression machine learning model**.

The system trains on historical loan data and learns patterns such as income, credit score, and assets to predict loan approval for new applicants.

---

## 🧠 Machine Learning Workflow

1. Load dataset
2. Handle missing values
3. Encode categorical variables
4. Normalize numerical features
5. Split dataset into training and testing sets
6. Train a Logistic Regression model
7. Evaluate model performance
8. Predict loan approval for a new applicant

---

## ⚙️ Technologies Used

* Python
* pandas
* scikit-learn

---

## 📊 Model Used

**Logistic Regression**

Why Logistic Regression?

* Suitable for binary classification problems
* Interpretable model
* Efficient for structured datasets

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 📂 Project Structure

```
02_loan_approval_ml
│
├── main.py
└── README.md
```

---

## ▶️ How to Run

Install dependencies:

```
pip install pandas scikit-learn
```

Run the program:

```
python main.py
```

---

## 💡 Example Output

```
Accuracy: 0.91

Confusion Matrix:
[[85 10]
 [ 8 97]]

Loan Status: Approved
```

---

## 🚀 Future Improvements

Possible enhancements:

* Try different ML models (Random Forest, XGBoost)
* Hyperparameter tuning
* Build a web interface for predictions
* Deploy as a small API

---

## 👩‍💻 Author

Ayushi Mishra
Computer Science Student

Learning journey:

* Python programming
* Machine learning
* data analysis
