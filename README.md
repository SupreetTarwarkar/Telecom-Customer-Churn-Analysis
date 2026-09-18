<div align="center"><h1>Telecom Customer Churn Analysis</h1></div>

<div align="center"><img src="https://raw.githubusercontent.com/SupreetTarwarkar/SupreetTarwarkar/main/Profile-Assets/section-line.svg" width="82%" alt="section divider"/></div>
<div align="center"><b>SHORT DESCRIPTION / PURPOSE</b></div>

An exploratory **Telecom Customer Churn Analysis** project built using **Python, Pandas, NumPy, Matplotlib, and Seaborn** to analyze **7,043 telecom customers** across demographic, service, billing, contract, and account attributes.

The analysis identifies customer churn patterns and highlights customer segments that may require targeted retention strategies.

<div align="center"><h1>Tech Stack</h1></div>

The analysis was built using the following tools and technologies:

- **Python** - Data analysis and exploratory data analysis
- **Google Colab** - Notebook development environment
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

<div align="center"><h1>Data Source</h1></div>

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

<div align="center"><h1>Business Problem</h1></div>

Customer churn directly affects recurring revenue and customer lifetime value in the telecom industry.

Understanding which customer groups are more likely to leave can help businesses identify areas where customer experience and retention strategies may need improvement.

<div align="center"><h1>Goal of the Analysis</h1></div>

- Measure the overall customer churn level
- Analyze customer demographics, services, billing, and account characteristics
- Compare churn across contract types and internet services
- Examine churn patterns across payment methods, dependents, and tech support
- Compare monthly charges between churned and retained customers
- Identify customer segments that may require focused retention efforts

<div align="center"><h1>Data Cleaning & Preparation</h1></div>

The notebook includes the following data-quality checks and preparation steps:

- Reviewed dataset structure, dimensions, and data types
- Checked duplicate records
- Converted **Total Charges** to a numeric field
- Identified **11 missing values** in Total Charges
- Replaced missing Total Charges values with the **median** because the distribution was right-skewed
- Verified the cleaned dataset before exploratory analysis

<div align="center"><h1>Exploratory Data Analysis</h1></div>

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

<div align="center"><h1>Key Findings & Business Insights</h1></div>

- **26.5% of customers churned**, while **73.5% remained**, indicating a meaningful customer-retention challenge.
- **Month-to-Month customers show the strongest churn concentration** compared with customers on longer contracts.
- **Fiber Optic is the largest internet-service segment at approximately 44% of customers** and also shows the highest churn levels among the internet-service groups analyzed.
- Customers who churned generally show **higher Monthly Charges** compared with customers who stayed.
- Customers using **Electronic Check** show the highest churn levels among the payment methods analyzed.
- Customers without **Tech Support** show higher churn levels than customers with Tech Support.
- These patterns highlight potential opportunities around contract conversion, pricing, customer support, service experience, and retention initiatives.

<div align="center"><h1>Analysis Visuals</h1></div>

<div align="center"><img src="https://raw.githubusercontent.com/SupreetTarwarkar/SupreetTarwarkar/main/Profile-Assets/section-line.svg" width="82%" alt="section divider"/></div>
<div align="center"><b>1. OVERALL CHURN DISTRIBUTION</b></div>

![Overall Churn Distribution](Images/1.%20Churn%20Rate.png)

The majority of customers remained with the company, while approximately **26.5% of customers churned**.

<div align="center"><img src="https://raw.githubusercontent.com/SupreetTarwarkar/SupreetTarwarkar/main/Profile-Assets/section-line.svg" width="82%" alt="section divider"/></div>
<div align="center"><b>2. CONTRACT TYPE DISTRIBUTION</b></div>

![Contract Type Distribution](Images/2.%20Churn%20by%20Contract.png)

Month-to-Month contracts represent the largest customer group, while One-Year and Two-Year contracts have comparatively fewer customers.

<div align="center"><img src="https://raw.githubusercontent.com/SupreetTarwarkar/SupreetTarwarkar/main/Profile-Assets/section-line.svg" width="82%" alt="section divider"/></div>
<div align="center"><b>3. INTERNET SERVICE DISTRIBUTION</b></div>

![Internet Service Distribution](Images/3.%20Churn%20by%20Internet%20Service.png)

Fiber Optic is the most commonly used internet service, followed by DSL, while a smaller group of customers does not use internet service.

<div align="center"><img src="https://raw.githubusercontent.com/SupreetTarwarkar/SupreetTarwarkar/main/Profile-Assets/section-line.svg" width="82%" alt="section divider"/></div>
<div align="center"><b>4. MONTHLY CHARGES VS CHURN</b></div>

![Monthly Charges vs Churn](Images/4.%20Monthly%20Charges%20vs%20Churn.png)

Customers who churned generally show higher Monthly Charges compared with customers who remained.

<div align="center"><h1>Dataset</h1></div>

The complete source dataset used for the analysis is available here:

- [`telecom_churn_data.csv`](Dataset/telecom_churn_data.csv)

The `Dataset` folder also contains additional information about the dataset structure and attributes.

<div align="center"><h1>Python Notebook</h1></div>

The complete exploratory data analysis notebook is available here:

- [`Telecom_Customer_Churn.ipynb`](Notebook/Telecom_Customer_Churn.ipynb)

The notebook includes:

- Data loading and inspection
- Data cleaning
- Exploratory data analysis
- Visualizations
- Written observations
- Key findings
- Retention-focused insights

<div align="center"><h1>Google Colab</h1></div>

The original analysis was developed using Google Colab:

[Open Telecom Customer Churn Analysis in Google Colab](https://colab.research.google.com/drive/1FkYdMHO0BLvu9o0FK0ycKMVkmaWd65c4?authuser=1)

<div align="center"><h1>Author</h1></div>

**Supreet Tarwarkar**

- [GitHub](https://github.com/SupreetTarwarkar)
- [LinkedIn](https://www.linkedin.com/in/supreettarwarkar/)
