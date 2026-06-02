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
The full ranking of our top-performing products by volume and revenue can be found directly in the data export file here: [top_products.csv](./data_exports/top_products.csv).


### 2. Which customers spend the most?
*Identifies top-tier lifetime value (LTV) VIP buyers based on cumulative spending.*


| Customer Name | Total Orders | Total Lifetime Spend ($) |
| :--- | :--- | :--- |
| [Insert Name 1] | [Insert Count] | $[Insert Spend] |
| [Insert Name 2] | [Insert Count] | $[Insert Spend] |

### 3. Which month generated the highest revenue?
*Highlights cyclical seasonal peaks and the absolute highest-grossing calendar month.*

* **Highest Revenue Month:** `[Insert YYYY-MM]`
* **Total Monthly Revenue:** `$[Insert Amount]`
* **Total Transactions:** `[Insert Number of Orders]`

### 4. What are the sales trends over time?
*Chronological review of monthly performance showing market trajectory.*

* **Growth Summary:** [Write a quick 1-2 sentence summary of whether your sales are going up, staying flat, or dropping as time moves forward].

---

## 🚀 How to Run the Analysis Locally
1. Clone this repository to your local machine.
2. Ensure **MySQL Server** is running on your localhost.
3. Import your source dataset into a schema named `sales_analysis` and name the table `sales`.
4. Open the `sales_analysis.sql` file in **MySQL Workbench**.
5. Execute the queries sequentially to populate the results grid.
