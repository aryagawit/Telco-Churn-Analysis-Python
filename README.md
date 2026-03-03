# 📡 Telco Customer Churn Prediction & Revenue Risk Analysis

## 📌 Project Overview
Customer churn (attrition) is one of the biggest challenges in the telecommunications industry. This project utilizes Python to analyze customer behavior patterns and build a predictive model to identify at-risk customers. 

The goal is not just to predict who leaves, but to understand **why** they leave and calculate the **financial impact** on the business.

## 🛠️ Tech Stack & Skills
* **Language:** Python 3.8+
* **Libraries:** Pandas (Data Manipulation), Seaborn/Matplotlib (Visualization), Scikit-Learn (Machine Learning)
* **Modeling:** Logistic Regression for Binary Classification
* **Metrics:** Accuracy, Precision, Recall, and Revenue-at-Risk calculation



## 🔍 Analytical Workflow
1. **Data Cleaning:** Handled missing values in `TotalCharges` and converted categorical features into numerical formats.
2. **Exploratory Data Analysis (EDA):** Identified that **Month-to-Month contracts** and **fiber optic users** have the highest probability of churning.
3. **Machine Learning:** Built a Logistic Regression model to classify customers likely to churn.
4. **Business Strategy:** Calculated the total Monthly Revenue at Risk and estimated potential savings through proactive retention.

## 📊 Key Business Insights
* **The "Month-to-Month" Trap:** Customers without long-term contracts are 3x more likely to churn.
* **Monthly Charges:** Higher monthly bills correlate strongly with customer exit, suggesting a need for loyalty discounts.
* **Revenue Impact:** The model identified over **$45,000** in monthly revenue that could be lost without intervention.



## 🚀 How to Run
1. Clone the repository.
2. Ensure you have the `telco_churn.csv` in the root directory.
3. Open `01_data_exploration.ipynb` in Jupyter Notebook or VS Code.
