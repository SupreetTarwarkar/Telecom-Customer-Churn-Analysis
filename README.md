# Telecom Customer Churn Analysis

## Short Description / Purpose

An exploratory **Telecom Customer Churn Analysis** project built using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** to analyze **7,043 telecom customers** across demographic, service, billing, contract, and account attributes. The analysis identifies churn patterns and customer segments that may require targeted retention strategies.

---

# Tech Stack

The analysis was built using the following tools and technologies:

- **Python** : Data analysis and exploratory analysis
- **Google Colab** : Notebook development environment
- **Pandas** : Data manipulation and cleaning
- **NumPy** : Numerical operations
- **Matplotlib** : Data visualization
- **Seaborn** : Statistical data visualization

---

# Data Source

The project uses a telecom customer churn dataset containing:

- **7,043 customer records**
- **21 columns**
- Customer demographics
- Tenure and account information
- Phone and internet services
- Online security, backup, device protection, and tech support
- Streaming services
- Contract type
- Payment method and paperless billing
- Monthly and total charges
- Customer churn status

---

# Features / Highlights

## Business Problem

Customer churn directly affects recurring revenue and customer lifetime value in the telecom industry. Understanding which customer groups are more likely to leave helps businesses focus retention efforts on the segments showing the strongest churn patterns.

---

## Goal of the Analysis

- Measure the overall customer churn level
- Analyze customer demographics, services, billing, and account characteristics
- Compare churn across contract types and internet services
- Examine churn patterns across payment methods, dependents, and tech support
- Compare monthly charges between churned and retained customers
- Identify actionable customer-retention opportunities

---

# Data Cleaning & Preparation

The notebook includes data-quality checks and preparation before analysis:

- Reviewed dataset structure, dimensions, and data types
- Checked duplicate records
- Converted **Total Charges** to a numeric field for analysis
- Identified **11 missing values** in Total Charges
- Replaced missing Total Charges values with the **median** because the distribution is right-skewed
- Verified the cleaned dataset before exploratory analysis

---

# Exploratory Data Analysis

The analysis covers:

- Overall churn distribution
- Contract type distribution
- Internet service distribution
- Customer tenure distribution
- Monthly Charges distribution
- Total Charges distribution
- Churn by contract type
- Churn by internet service
- Churn by payment method
- Monthly Charges vs churn
- Churn by dependents
- Churn by tech support
- Internet service, Monthly Charges, and churn interaction

---

# Business Impact & Insights

- **26.5% of customers churned**, while **73.5% remained**, showing a meaningful retention challenge.
- **Month-to-Month customers show the strongest churn concentration** compared with longer contract types.
- **Fiber Optic is the largest internet-service segment at 44% of customers** and also shows the highest churn levels among the internet-service groups analyzed.
- Customers who churned generally show **higher Monthly Charges** than customers who stayed.
- **Electronic Check** customers show the highest churn levels among the payment methods analyzed.
- Customers without **Tech Support** show higher churn levels than customers with Tech Support.
- These patterns indicate opportunities to strengthen onboarding, contract conversion, pricing, service experience, and support-based retention strategies.

---

# Analysis Visuals

The project notebook generates the key analysis visuals directly using **Matplotlib** and **Seaborn**, including churn distribution, contract analysis, internet-service analysis, payment-method analysis, monthly-charge comparison, dependents, and tech-support analysis.

---

# Dataset

The analysis uses the following source file:

- `telecom_churn_data.csv`

The **Dataset** folder is included for project organization. The raw CSV should be added only when the source file is available for redistribution.

---

# Python Notebook

The GitHub-ready exploratory analysis notebook is included in this repository:

- `Notebook/Telecom_Customer_Churn.ipynb`

The notebook includes data cleaning, exploratory analysis, visualizations, written observations, and retention-focused insights.

### Original Google Colab Analysis

https://colab.research.google.com/drive/1FkYdMHO0BLvu9o0FK0ycKMVkmaWd65c4?authuser=1

---

## 👤 Author

**Supreet Tarwarkar**

- GitHub: https://github.com/SupreetTarwarkar
- LinkedIn: https://www.linkedin.com/in/supreettarwarkar/
