
# 📊 Random Forest - Telco Customer Churn Prediction

## 📌 Project Overview

This project uses Machine Learning to predict whether a telecom customer is likely to leave the company (Churn) using the **Random Forest Classification Algorithm**.

The main objective is to analyze customer information and identify the factors that influence customer churn.

## 📂 Dataset Information

- **Dataset Name:** Telco Customer Churn
- **Source:** Kaggle
- **Total Records:** 7,043
- **Total Columns:** 21
- **Problem Type:** Classification

🔗 **Dataset Link:**  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## 🎯 Problem Statement

Telecommunication companies face the problem of customers discontinuing their services. This project aims to predict customer churn using customer details such as tenure, monthly charges, total charges, contract type, and other service-related information.

The model helps identify customers who may leave the company so that suitable steps can be taken to improve customer retention.

## 🛠️ Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

The following steps were performed:

1. **Importing Libraries:** Imported the required Python libraries.
2. **Loading Dataset:** Loaded the Telco Customer Churn dataset.
3. **Data Exploration:** Examined the dataset using shape, information, and statistical summaries.
4. **Data Preprocessing:**
   - Converted `TotalCharges` into numeric format.
   - Handled missing values using median imputation.
   - Removed the unnecessary `customerID` column.
   - Encoded categorical variables.
5. **Splitting Dataset:** Divided the dataset into 80% training data and 20% testing data.
6. **Model Building:** Implemented the Random Forest Classifier with 100 decision trees.
7. **Model Evaluation:** Evaluated the model using classification metrics.
8. **Feature Importance:** Identified the important features influencing customer churn.
9. **Hyperparameter Tuning:** Used GridSearchCV to improve model performance.
10. **Cross-Validation:** Used 5-fold cross-validation to check model performance.

## 🤖 Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is a supervised machine learning algorithm that combines multiple decision trees to make predictions. It is used here to classify customers into two categories:

- **0 – No Churn:** Customer continues using the service.
- **1 – Yes Churn:** Customer leaves the service.

## 📈 Model Evaluation

The original Random Forest model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 78.92% |
| Precision | 0.643 |
| Recall | 0.458 |
| F1 Score | 0.535 |

### Hyperparameter Tuning Results

After applying GridSearchCV, the tuned model achieved:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 81.41% |
| Precision | 0.698 |
| Recall | 0.525 |
| F1 Score | 0.599 |

The tuned model showed improvement in all four evaluation metrics.

## 🔍 Key Findings

- TotalCharges, tenure, and MonthlyCharges were among the most important features.
- Customer tenure plays an important role in predicting churn.
- Hyperparameter tuning improved the model's performance.
- The tuned Random Forest model performed better than the original model.

## ✅ Conclusion

The project successfully demonstrates the use of the Random Forest Classification algorithm for predicting customer churn in the telecom industry.

The model was evaluated using accuracy, precision, recall, and F1 score. Hyperparameter tuning improved the overall performance of the model.

This project helped understand the practical application of Machine Learning in solving a real-world business problem.

## 📁 Project Files

- `Project4.ipynb` – Jupyter Notebook containing the complete Python implementation.
- `Telco_Customer_Churn_Random_Forest_Report_Anushka.pdf` – Project report.

## 👩‍💻 Author

**Anushka Kiran Gundale**

B.Tech Student

---

⭐ If you find this project useful, feel free to explore the notebook and dataset!
