#Telco Customer Churn - Exploratory Data Analysis (EDA)
📌 Project Overview

This project focuses on analyzing customer churn data for a telecom company.
The goal is to explore patterns, customer behavior, and key factors that contribute to churn.
By performing Exploratory Data Analysis (EDA), we uncover actionable insights that can help improve customer retention strategies.

📂 Dataset

Source: Telco Customer Churn dataset (commonly available on Kaggle
)

Rows: ~7,000 customer records

Columns: Customer demographics, services subscribed, contract/payment details, and churn flag

Key Features:

CustomerID – Unique identifier for each customer

Gender, SeniorCitizen, Partner, Dependents – Demographics

Tenure, Contract, PaymentMethod – Subscription details

MonthlyCharges, TotalCharges – Revenue-related features

Churn – Target variable (Yes/No)

🔎 EDA Highlights

Replaced missing or blank values in TotalCharges with 0 when tenure = 0.

Converted SeniorCitizen values from 0/1 to No/Yes for better readability.

Churn Rate: ~26.5% of customers have churned.

Senior Citizens show a higher churn percentage compared to younger customers.

Tenure Effect: Customers with short tenure (1–2 months) are more likely to churn, while long-term customers tend to stay.

Services Impact:

Customers with PhoneService, DSL Internet, and OnlineSecurity have lower churn rates.

Lack of TechSupport, OnlineBackup, StreamingTV is associated with higher churn.

Payment Method: Customers paying via Electronic Check are more likely to churn.

📊 Visualizations

Pie chart of churn distribution

Bar plots for categorical features vs churn (e.g., Contract, InternetService)

Tenure and Monthly Charges analysis

Comparative churn rate across different services and demographics

🛠 Tools & Libraries

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for analysis & visualization

🚀 How to Run

Clone the repository

git clone https://github.com/your-username/Telco-Customer-Churn-EDA.git
cd Telco-Customer-Churn-EDA


Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook TCA.ipynb

📌 Key Insights

Long-term contracts and bundled services reduce churn.

Senior citizens and electronic check users are at high churn risk.

Providing security/backup services and encouraging auto-payment methods can improve retention.

📄 License

This project is open-source and available under the MIT License.
