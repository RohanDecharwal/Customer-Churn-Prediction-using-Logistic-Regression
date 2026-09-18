## Customer Churn Prediction using Logistic Regression

### 👨‍🎓 Student Details

- **Name:** Rohan Ramdhan Decharwal
- **Course:** AI/ML Internship
- **Batch:** Batch 1(A)
- **Mentor:** Nishant Shrivastava

---

## 📌 Objective

The objective of this project is to develop a **Logistic Regression** model to predict whether a telecommunications customer is likely to churn based on demographic information and service usage. This project demonstrates the complete machine learning workflow, including data preprocessing, feature encoding, model training, evaluation, and interpretation of classification results.

---

## 📂 Dataset

**Telco Customer Churn Dataset**

🔗 **Kaggle Dataset:**  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Features

The dataset contains customer demographic details, account information, subscribed services, contract details, payment methods, and billing information.

**Target Variable**

- Churn (Yes/No)

---

## 🛠 Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Methodology

The project was completed using the following steps:

1. Loaded the dataset using Pandas.
2. Explored the dataset and identified numerical and categorical features.
3. Checked for missing values and handled them where necessary.
4. Encoded categorical variables using suitable encoding techniques.
5. Split the dataset into **80% training** and **20% testing**.
6. Trained a **Logistic Regression** classification model.
7. Predicted customer churn on the test dataset.
8. Evaluated the model using:
   - Accuracy Score
   - Precision
   - Recall
   - F1-Score
9. Generated a **Confusion Matrix** to analyze prediction performance.

---

## 📊 Results

The Logistic Regression model successfully classified customers as likely to churn or not churn. The model's performance was evaluated using Accuracy, Precision, Recall, and F1-Score. The Confusion Matrix provided insights into correctly classified and misclassified customers, helping assess the model's effectiveness in predicting customer churn.

---

## 📝 Conclusion

This project demonstrates the use of Logistic Regression for customer churn prediction using demographic and service-related information. The analysis indicates that factors such as contract type, monthly charges, tenure, and internet services significantly influence customer churn. Logistic Regression provides a simple and interpretable approach for binary classification problems and serves as a strong baseline model. However, one limitation of Logistic Regression is that it assumes a linear relationship between the input features and the log-odds of the target variable, which may not fully capture complex patterns in customer behavior. More advanced classification models may achieve better predictive performance.

---

## 📁 Repository Structure

```
Customer Churn Prediction using Logistic Regression/
│── Customer Churn Prediction using Logistic Regression.ipynb
│── README.md
```

---

## 👤 Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship – Batch 1(A)**

**Mentor:** Nishant Shrivastava
