📊 Bank Customer Churn Analysis

📌 Overview
This project analyzes 10,000 bank customer records (18 variables) to identify the main drivers of customer churn and provide data-driven retention strategies.
Churn analysis is critical for banks to reduce revenue loss, improve customer loyalty, and optimize marketing campaigns.

📂 Dataset
Source: Kaggle – Bank Customer Churn dataset
Size: 10,000 records × 18 features
Key variables:
CustomerId, Surname, Geography, Gender, Age
Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember
EstimatedSalary, Exited (target = churn)

⚙️ Methods & Tools
Languages & Libraries: Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL: Query for churn segmentation
Visualization: Power BI dashboards for churn insights
Techniques:
Data Cleaning & Feature Engineering
Exploratory Data Analysis (EDA)
Customer segmentation by demographics & financial behavior
Churn rate calculation by group

🔍 Key Findings
Overall churn rate: 20.38% (2,038 customers).
Demographic insights:
Age 40–59 group has the highest churn.
Female churn rate = 25%, higher than male (11.5%).
Germany has the highest churn rate (32.4%) compared to France & Spain.
Behavioral & financial insights:
Customers with complaints churn at 99.5% → almost certain.
Customers with 2 products have the lowest churn (8.2%).
Tenure = 7 years group has the lowest churn (17.2%).

📊 Results & Business Impact
Built churn dashboards to visualize high-risk segments.
Identified churn risk factors: gender, geography, age, complaints, product usage.
Suggested retention strategies:
Early-warning system for high-risk groups.
Special retention programs for female, middle-aged, and German customers.
Complaint resolution system within 24 hours.

📸 Sample Dashboard
(👉 Bạn có thể chèn ảnh Power BI hoặc matplotlib plot vào đây, ví dụ:)

![Churn Dashboard](images/churn_dashboard.png)

📂 Project Structure
Bank_Customer_Churn/
│-- data/
│   └── Bank_Churn.csv
│-- notebooks/
│   └── churn_analysis.ipynb
│-- dashboards/
│   └── churn_powerbi.pbix
│-- images/
│   └── churn_dashboard.png
│-- README.md

🚀 Next Steps
Build a predictive churn model (Logistic Regression, Random Forest, XGBoost).
Deploy a churn prediction API for HR/CRM system.
Automate churn reports with Power BI Service.

👤 Author
To Huynh Ngoc Ngan
Data Analyst | SQL | Python | Power BI

LinkedIn
 | [GitHub](https://github.com/celine1252/)
