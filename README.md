Customer Shopping Behavior Analysis

A complete end-to-end data analytics project analyzing customer shopping patterns using Python, SQL Server, and Power BI. The project covers data loading, EDA, cleaning, SQL analysis, dashboard creation, insight reporting, and final presentation using Gamma.

🚀 Overview
This project explores customer purchasing behaviour across ~3,900 transactions to uncover insights on spending patterns, product preference, segmentation, and subscription trends.  
It demonstrates the full analytics workflow and showcases practical skills for real-world business analysis.

📂 Dataset
- **Rows:** ~3,900 transactions  
- **Features:** purchase_amount, category, previous_purchases, subscription_status, discount_applied, item_purchased, etc.  
- **Source:** Provided dataset  

🛠️ Tools & Technologies
- **Python** – Pandas, NumPy, pyodbc, sqlalchemy  
- **SQL Server (T-SQL)** – Segmentation, aggregations, behavioural analysis  
- **Power BI** – Interactive dashboard  
- **Gamma App** – Project presentation deck  
- **Jupyter Notebook** – Data exploration & documentation


 # Customer Shopping Behavior Analysis

A complete end-to-end data analytics project analyzing customer shopping patterns using Python, SQL Server, and Power BI. The project covers data loading, EDA, cleaning, SQL analysis, dashboard creation, insight reporting, and final presentation using Gamma.

---

## 🚀 Overview
This project explores customer purchasing behaviour across ~3,900 transactions to uncover insights on spending patterns, product preference, segmentation, and subscription trends.  
It demonstrates the full analytics workflow and showcases practical skills for real-world business analysis.

---

## 📂 Dataset
- **Rows:** ~3,900 transactions  
- **Features:** purchase_amount, category, previous_purchases, subscription_status, discount_applied, item_purchased, etc.  
- **Source:** Provided dataset  

---

## 🛠️ Tools & Technologies
- **Python** – Pandas, NumPy, Matplotlib, Seaborn  
- **SQL Server (T-SQL)** – Segmentation, aggregations, behavioural analysis  
- **Power BI** – Interactive dashboard  
- **Gamma App** – Project presentation deck  
- **Jupyter Notebook** – Data exploration & documentation  

---

## 📘 Project Structure


📘 Project Structure
📁 Customer-Shopping-Behavior-Analysis
│
├── README.md
├── Customer_Shopping_Behavior_Analysis.ipynb     # Python EDA & Cleaning
├── customer_shopping_behaviour_sql_query.sql      # SQL Analysis
├── customer_behaviour_dashboard.pbix              # Power BI Dashboard
└── online reports @ https://customer-shopping-behavi-wgjfaos.gamma.site/
└── Customer-Behavior-Analysis.pptx                   # Final Presentation

🔍 Project Steps

**1. Data Loading (Python)**
  - Imported dataset into Jupyter Notebook  
  - Inspected schema, datatypes, missing values  

**2. Exploratory Data Analysis**
  - Summary statistics  
  - Spending distribution  
  - Product category analysis  
  - Customer behavioural trends  

**3. Data Cleaning**
  - Removed duplicates  
  - Imputed missing values  
  - Standardized formats  
  - Feature engineering (segmentation, value grouping)

**4. SQL Analysis (SQL Server)**
    Executed analytical queries including:
    - Customer segmentation (New, Returning, Loyal)  
    - Top 3 items per category  
    - Discount usage vs average spending  
    - Subscription likelihood for repeat customers  

**5. Power BI Dashboard**
    Created a multi-page interactive dashboard showing:
    - Revenue trend & KPIs  
    - Segmentation distribution  
    - Product category performance  
    - Subscription behaviour  
    - Filters for category, customer type, and discount use  

**6. Reporting**
    Produced insight summary covering:
    - Key patterns discovered  
    - Customer behaviour drivers  
    - Business recommendations  

**7. Presentation (Gamma)**
    Developed a polished slide deck summarizing workflow, visuals, and insights.

📊 Dashboard Highlights
    - Customer segmentation overview  
    - Top-performing categories & items  
    - Discount impact analysis  
    - Subscription behaviour trends  

🧠 Key Insights
    - Loyal customers are strong candidates for subscription upsell  
    - Certain categories significantly outperform others in revenue  
    - Discounts don’t always correlate with lower spending  
    - Repeat buyers contribute high lifetime value  

▶️ How to Run This Project

  **1. Run Python Notebook**
      Install dependencies:
      ```bash
      pip install pandas numpy pyodbc sqlalchemy
      ````

    Open and run:
      ```
      Customer_Shopping_Behavior_Analysis.ipynb
      ```

**2. Run SQL Queries**
    * Open SQL Server Management Studio (SSMS)
    * Load dataset
    * Execute:
      ```
        customer_shopping_behaviour_sql_query.sql
      ```

**3. Open Power BI Dashboard**
      * Open `customer_behaviour_dashboard.pbix` in Power BI Desktop
      * Refresh the data if needed

**4. View the Presentation**
      * Open `reports/presentation_gamma.pdf`

🤝 Contributions
    Contributions, issues, and suggestions are welcome!



