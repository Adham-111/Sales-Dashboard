# Sales Performance Dashboard: An End-to-End Analytics Project

This project shows how raw sales data can be turned into an interactive dashboard.  
It covers the main steps of data cleaning, modeling, and visualization, and gives a full example of an end-to-end analytics workflow.  



https://github.com/user-attachments/assets/c7cfd67b-fd51-45f7-85f8-f6a3b9531194




## 1. Project Overview

Our primary goal is to provide stakeholders with a comprehensive view of sales performance. We achieve this by:
* Establishing a **clean and reliable single source of truth** for all sales data.
* Building a **scalable data model** optimized for analytics.
* Calculating **critical business KPIs** with precision.
* Developing an **interactive dashboard** that empowers users to explore data and uncover insights.

## 2. Technical Workflow

### Step 1: Data Ingestion and Cleansing
The raw `Sales.csv` file is the starting point. Data is ingested, and a series of data cleaning and preprocessing steps are performed to handle any missing values, correct data types, and standardize formats. This ensures data integrity and reliability for downstream analysis.

### Step 2: Data Modeling for Performance
To address the limitations of a flat file and improve query performance, we transform the data into a **star schema**. This model separates data into:
* A **fact table** (e.g., `SalesFact`) containing numerical metrics like `LineTotal` and `OrderQty`.
* **Dimension tables** (e.g., `DimDate`, `DimProduct`, `DimTerritory`) that provide descriptive attributes.

This structure minimizes data redundancy and significantly accelerates dashboard responsiveness.

### Step 3: KPI Calculation with DAX
Key performance indicators are defined and calculated using **DAX (Data Analysis Expressions)**. We create measures for metrics such as:
* `Total Sales`
* `Total Order Quantity`
* `Sales per Territory`
* `Top-Selling Products`

Using DAX ensures that these metrics are dynamic and update automatically with any filter or selection in the dashboard.

### Step 4: Interactive Dashboard Development
An interactive dashboard is built to visualize the processed data and calculated KPIs. The dashboard is designed with user experience in mind, allowing for intuitive navigation and deep-dive analysis. Key visualizations include:
* A Tree map to track the Most selling products .
* Bar charts to compare performance across product categories and shipping methods.
* Trend lines to track sales over time.

## 3. Key Insights

The dashboard reveals critical business intelligence:
* **Total Sales of over $53.96M:** A robust top-line performance.
* **Canda is the dominant market:** A key area for continued investment.
* **Components are the top-selling products:** Indicating a strong product-market fit.
* **CARGO TRANSPORT 5 is the primary logistics channel:** Highlighting the need to monitor and optimize this method.
* **Products :** Awc Logo cap and Long sleeve logo jensy  has the best no of orders 
* **Track custmoer purchasing** by using the filter in the dashboard
* **Track sales person  Performance** by using the filter in the dashboard

---

## 📌 Recommendations

- **Focus on What Works:** Invest more in top-performing regions (like **Canada**) and strong product categories (such as Components) to increase sales growth.  
- **Save Costs in Shipping:** Review the main shipping method (**CARGO TRANSPORT 5**) to see if cheaper or faster options are available.  
- **Use Data for Decisions:** Encourage teams to rely on the interactive dashboard for real-time insights instead of guesswork.  
- **Track Customer Performance:** Monitor key customers to identify loyal buyers and spot opportunities for upselling or cross-selling.  
- **Evaluate Salesperson Performance:** Regularly check sales by each representative to reward high performers and provide support or training where needed.  




**Add your new recommendations here:**
* **Placeholder for Recommendation 1:** [Provide a new recommendation based on your new insights, e.g., "Implement a Q4 marketing campaign to capitalize on historical sales trends."]
* **Placeholder for Recommendation 2:** [Add a second recommendation, e.g., "Develop a loyalty program targeting top customers to increase their lifetime value."]
