# 📊 MySQL Sales & Customer Analysis Project

## 🔍 Project Description
This repository contains a comprehensive data analysis project using **MySQL** to investigate a local retail dataset. The objective is to transform raw sales transaction data into actionable business intelligence by answering core revenue, product performance, and customer demographic questions. 

By executing optimized SQL queries against a single consolidated transactions database, this project identifies top-performing items, pinpoints high-value buyers, and maps out chronological growth trends over time.

---

## 🛠️ Tech Stack & Environment
* **Database Engine:** MySQL Server (Hosted via Localhost via phpMyAdmin)
* **Database Management GUI:** MySQL Workbench
* **Language:** SQL (Structured Query Language)
* **Version Control:** Git & GitHub

---

## 💾 Database Schema Details
The analysis was performed on a unified table named `sales` within the `sales_analysis` schema. The dataset includes the following structural layout:
* **Transaction Identifiers:** `order_id`, `product_id`, `customer_id`, `review_id`
* **Temporal Attributes:** `order_date`, `review_date`, `signup_date`
* **Customer Demographics:** `first_name`, `last_name`, `gender`, `age_group`, `country`
* **Product Details:** `product_name`, `category`, `unit_price`
* **Transactional Metrics:** `quantity`, `order_status`, `payment`
* **Feedback Metrics:** `rating`, `review_text`

---

## 📈 Key Insights & Results

### 1. Which products sell the most?
*The data reveals the top-performing inventory items by total unit volume sold and absolute revenue generated.*

👉 **View Dataset:** [https://github.com/RC1010/MySQL-Sales-Customer-Analysis-Project/blob/main/SQL%20Sales%20Analysis/Data/top_products.csv]

### 2. Which customers spend the most?
*Identifies top-tier lifetime value (LTV) VIP buyers based on cumulative spending.*

👉 **View Dataset:** [https://github.com/RC1010/MySQL-Sales-Customer-Analysis-Project/blob/main/SQL%20Sales%20Analysis/Data/top_customers.csv]

### 3. Which month generated the highest revenue?
*Highlights cyclical seasonal peaks and the absolute highest-grossing calendar month.*

👉 **View Dataset:** [https://github.com/RC1010/MySQL-Sales-Customer-Analysis-Project/blob/main/SQL%20Sales%20Analysis/Data/highest_revenue_months.csv]

### 4. What are the sales trends over time?
*Chronological review of monthly performance showing market trajectory.*

👉 **View Dataset:** [https://github.com/RC1010/MySQL-Sales-Customer-Analysis-Project/blob/main/SQL%20Sales%20Analysis/Data/sales_trends_timeline.csv]

---

## 🚀 How to Run the Analysis Locally
1. Clone this repository to your local machine.
2. Ensure **MySQL Server** is running on your localhost.
3. Import your source dataset into a schema named `sales_analysis` and name the table `sales`.
4. Open your query file in **MySQL Workbench**.
5. Execute the queries sequentially to populate the results grid.
