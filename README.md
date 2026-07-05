# **📊 Telecom Customer Churn Analysis (Exploratory Data Analysis)**
### *An Exploratory Data Analysis (EDA) Project for Understanding Customer Churn Patterns and Retention Drivers*
The Telecom Customer Churn Analysis is an end-to-end Exploratory Data Analysis (EDA) project developed using Python to investigate the key factors influencing customer churn in the telecom industry. The project analyzes customer demographics, service subscriptions, account details, billing information, and contract types to uncover actionable insights that can help reduce churn and improve customer retention strategies.

# **📌 Short Description / Purpose**
This Exploratory Data Analysis project aims to identify customer behavior patterns that contribute to churn by analyzing telecom customer data. Through statistical analysis and visualizations, the project highlights important trends across customer demographics, service usage, contracts, billing, and payment methods to support data-driven retention strategies and lay the foundation for future predictive churn models.

# **🛠 Tech Stack**
The project was built using the following tools and technologies:
* 🐍 **Python** – Primary programming language for data analysis.
* 📊 **Pandas** – Data cleaning, manipulation, and preprocessing.
* 🔢 **NumPy** – Numerical operations and handling missing values.
* 📈 **Matplotlib** – Data visualization and plotting.
* 🎨 **Seaborn** – Statistical visualizations and exploratory analysis.
* 📒 **Jupyter Notebook / Google Colab** – Interactive environment for analysis and documentation.
* 📁 **Dataset Format**
  * `.csv` – Telecom Customer Churn dataset
  * `.ipynb` – Analysis notebook
  * 
# **📂 Data Source**
**Source:** Telco Customer Churn Dataset (Kaggle Sample Dataset)
The dataset contains **7,043 customer records** with information related to:
* Customer Demographics
* Account Information
* Contract Type
* Internet Services
* Phone Services
* Payment Methods
* Monthly Charges
* Total Charges
* Customer Tenure
* Technical Support
* Streaming Services
* Customer Churn Status
The data was cleaned by handling missing values, correcting data types, and performing preprocessing before conducting exploratory analysis.

# **✨ Features / Highlights**
## **📍 Business Problem**
Customer churn is one of the biggest challenges in the telecom industry because acquiring new customers is significantly more expensive than retaining existing ones.
Business stakeholders often need answers to questions such as:
* Which customers are most likely to churn?
* Does contract type influence customer retention?
* How do monthly charges affect churn?
* Which internet service has the highest churn?
* Does technical support improve customer retention?
* Which payment methods are associated with higher churn?
Without detailed exploratory analysis, identifying these patterns is difficult and limits the effectiveness of retention strategies.

# **🎯 Goal of the Project**
The primary objectives of this EDA project are to:
* Analyze customer churn distribution.
* Identify demographic and service-related factors affecting churn.
* Explore relationships between customer attributes and churn behavior.
* Discover actionable business insights for improving customer retention.
* Build a strong analytical foundation for future machine learning churn prediction models.

# **📊 Walkthrough of Key Analysis**
## **1. Customer Churn Distribution**
The analysis begins by examining the overall distribution of customers who stayed versus those who left the company.
This provides a high-level understanding of customer retention and overall churn rate.

## **2. Contract Type Analysis**
Customer distribution across different contract types is analyzed:
* Month-to-Month
* One-Year
* Two-Year
This helps determine how contract commitments influence customer loyalty.

## **3. Internet Service Analysis**
The project compares customer distribution among:
* Fiber Optic
* DSL
* No Internet Service
It also evaluates how different internet services impact customer churn.

## **4. Customer Tenure Analysis**
A histogram of customer tenure reveals how long customers remain with the company before leaving, helping identify high-risk periods during the customer lifecycle.

## **5. Billing Analysis**
Monthly Charges and Total Charges are analyzed using histograms and boxplots to understand pricing patterns and their relationship with customer churn.

## **6. Churn by Contract Type**
This analysis compares churn across different contract categories, highlighting which customers are most likely to discontinue services.

## **7. Churn by Payment Method**
Payment methods such as:
* Electronic Check
* Credit Card
* Bank Transfer
* Mailed Check
are compared to identify payment behaviors associated with higher churn rates.

## **8. Customer Support Analysis**
The relationship between Technical Support subscriptions and customer churn is explored to understand the impact of customer service on retention.

## **9. Demographic Analysis**
Customer demographics such as:
* Gender
* Senior Citizen
* Partner
* Dependents
are analyzed to identify population segments with higher churn tendencies.

## **10. Service Usage Analysis**
The project examines how additional telecom services—including Online Security, Device Protection, Streaming Services, and Backup Services—relate to customer retention and churn behavior.

## **11. Correlation & Comparative Analysis**
Multiple comparative visualizations evaluate interactions between:
* Internet Service vs Monthly Charges
* Monthly Charges vs Churn
* Dependents vs Churn
* Tech Support vs Churn
* Contract Type vs Churn
These analyses help uncover the strongest factors associated with customer churn.

# **📈 Business Impact & Insights**
### **Customer Retention Strategy**
The analysis identifies customer segments with the highest churn risk, enabling telecom providers to implement targeted retention campaigns.

### **Contract Optimization**
Customers on Month-to-Month contracts exhibit significantly higher churn, highlighting the opportunity to encourage migration to long-term contracts.

### **Pricing Strategy**
Higher monthly charges are associated with increased churn, suggesting the need for competitive pricing, bundled offers, or loyalty discounts for high-value customers.

### **Service Quality Improvement**
Fiber Optic customers experience higher churn rates, indicating potential opportunities to improve network quality, customer support, or pricing strategies.

### **Customer Support Enhancement**
Customers subscribed to Technical Support show lower churn, emphasizing the importance of proactive customer service in improving retention.

### **Predictive Analytics Foundation**
The insights gained through EDA provide a strong basis for developing machine learning models capable of predicting customer churn and enabling proactive intervention.

# **🔍 Key Insights**
* Approximately **26.5%** of customers have churned, while **73.5%** remain active, indicating a substantial opportunity to improve customer retention.
* Customers on **Month-to-Month contracts** are significantly more likely to churn than those with one-year or two-year agreements.
* **Fiber Optic** users exhibit the highest churn rates despite being the most widely adopted internet service, suggesting potential concerns related to pricing or service quality.
* Customers with **higher monthly charges** are more likely to discontinue the service, highlighting the importance of pricing strategies and value-added offerings.
* Users paying through **Electronic Check** experience higher churn compared to customers using automatic payment methods such as bank transfers or credit cards.
* Customers without **Technical Support** or **Dependents** demonstrate a higher likelihood of churning, emphasizing the role of customer support services and customer demographics in retention.
* The findings from this exploratory analysis provide actionable business insights that can help telecom companies reduce churn, improve customer satisfaction, and support the development of predictive churn models for proactive customer retention.
