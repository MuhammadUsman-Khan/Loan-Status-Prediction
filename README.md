# 🏦 Loan Status Prediction using Machine Learning

This project builds a machine learning model to predict whether a loan application will be approved or not based on applicant details using **Support Vector Machine (SVM)**.

---

## 🔍 Problem Statement

Loan approval is a critical decision-making process for financial institutions. This project aims to classify loan applications into two categories:

* Loan Not Approved (label = 0)

* Loan Approved (label = 1)

*⚠️ Note: The model's predictions are limited to the dataset and may not generalize well to real-world loan applications.*

---

## 📁 Dataset

**Source:** Kaggle Loan Prediction Dataset

**File Used:** Loan Prediction Dataset.csv

**Features:** 
  * Loan_ID 
  * Gender 
  * Married 
  * Dependents 
  * Education 
  * Self_Employed
  * ApplicantIncome 
  * CoapplicantIncome
  * LoanAmount 
  * Loan_Amount_Term 
  * Credit_History 
  * Property_Area
  * Loan_Status

---

## 🛠️ Technologies Used

* Python (Google Colab)

* Libraries: NumPy, Pandas, Seaborn

* Modeling: scikit-learn (SVM, train_test_split, accuracy_score)

  ---

## ⚙️ Data Preprocessing

* Handling Missing Values: Dropped rows with missing values

* Label Encoding: Converted categorical features (Gender, Married, Education, etc.) into numeric values

* Feature Selection: Removed Loan_ID as it does not impact prediction

* Data Splitting: Train-Test split (90% training, 10% testing)

---

## 🤖 Model Details

* **Algorithm:** *Support Vector Machine (SVM)* with *linear kernel*

* **Input:** Encoded and cleaned features of the applicants

* **Evaluation:** Accuracy score on both training and test data

---

## 📊 Results

* Successfully trained and evaluated the model

* Training Accuracy: **~79.8%**

* Test Accuracy: **~83.3%**

## 🧪 Usage

* Upload Loan Prediction Dataset.csv to your Colab session

* Run the notebook cells sequentially

* The notebook handles all preprocessing, training, and prediction steps

* Use the predictive system to test custom inputs

