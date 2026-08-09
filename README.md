# 📊 Amazon Sales & Customer Analytics Dashboard

An interactive **Power BI dashboard** built to analyze Amazon sales performance, customer behavior, product performance, delivery status, payment methods, and customer reviews using **15,000 e-commerce transactions from 2025**.

The project transforms raw sales data into actionable business insights through interactive KPIs, charts, filters, and customer/product analysis.

---

## 🚀 Project Overview

The **Amazon Sales & Customer Analytics Dashboard** provides a comprehensive view of e-commerce business performance across sales, customers, products, categories, locations, payments, deliveries, and customer satisfaction.

The dashboard was developed using **Microsoft Power BI**, with the underlying dataset prepared in Excel.

### 🎯 Objectives

* Analyze overall sales and revenue performance
* Identify top-performing products and categories
* Understand customer purchasing behavior
* Analyze sales across Indian states
* Monitor delivery performance
* Analyze payment method preferences
* Evaluate customer review ratings
* Identify business trends and opportunities
* Build an interactive dashboard for data-driven decision-making

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                  |
| ------------------- | ---------------------------------------- |
| **Power BI**        | Dashboard development & visualization    |
| **Power Query**     | Data cleaning & transformation           |
| **DAX**             | Calculated measures & KPIs               |
| **Microsoft Excel** | Dataset & data preparation               |
| **Data Analysis**   | Business insights & performance analysis |

---

## 📁 Project Structure

```text
Amazon-Sales-Customer-Analytics/
│
├── 📊 Amazon Sales & Customer Analytics Dashboard.pbix
├── 📄 amazon_sales_2025_INR.xlsx
└── 📖 README.md
```

---

## 📂 Dataset Information

The dataset contains **15,000 Amazon e-commerce transactions** from 2025.

### Dataset Dimensions

* **15,000** transactions
* **15,000** unique orders
* **7,259** unique customers
* **25** products
* **5** product categories
* **28** Indian states
* **44,770** total units sold
* **₹1.12 Billion** total sales
* **3.04 / 5** average review rating

### Dataset Columns

| Column             | Description                  |
| ------------------ | ---------------------------- |
| `Order_ID`         | Unique order identifier      |
| `Date`             | Order date                   |
| `Customer_ID`      | Unique customer identifier   |
| `Product_Category` | Product category             |
| `Product_Name`     | Name of the product          |
| `Quantity`         | Number of units purchased    |
| `Unit_Price_INR`   | Price per unit in INR        |
| `Total_Sales_INR`  | Total sales amount           |
| `Payment_Method`   | Payment method used          |
| `Delivery_Status`  | Delivery status of the order |
| `Review_Rating`    | Customer rating from 1–5     |
| `Review_Text`      | Customer review              |
| `State`            | Customer/order state         |
| `Country`          | Country                      |

---

## 📈 Key KPIs

The dashboard tracks important business metrics including:

* 💰 **Total Revenue**
* 🛒 **Total Orders**
* 👥 **Total Customers**
* 📦 **Total Quantity Sold**
* ⭐ **Average Customer Rating**
* 💳 **Payment Method Distribution**
* 🚚 **Delivery Status**
* 🏆 **Top Products**
* 📊 **Category Performance**
* 📍 **State-wise Sales**

### Current Dataset Summary

| KPI                 |        Value |
| ------------------- | -----------: |
| Total Sales         |   **₹1.12B** |
| Total Orders        |   **15,000** |
| Total Customers     |    **7,259** |
| Total Quantity Sold |   **44,770** |
| Average Order Value |  **₹74,544** |
| Average Rating      | **3.04 / 5** |
| Product Categories  |        **5** |
| Products            |       **25** |
| States              |       **28** |

---

## 📊 Dashboard Features

### 1. Executive Sales Overview

Provides a high-level view of the overall business performance through:

* Total Revenue
* Total Orders
* Total Customers
* Quantity Sold
* Average Rating
* Sales trends
* Category performance

---

### 2. Product & Category Analysis

The dashboard allows users to analyze:

* Top-selling products
* Best-performing categories
* Product-wise revenue
* Product quantity sold
* Category contribution to total sales
* Product performance comparison

This helps identify which products and categories contribute most to overall business performance.

---

### 3. Customer Analytics

Customer analysis focuses on:

* Customer purchase behavior
* Customer distribution
* Top customers
* Customer spending
* Order patterns
* Customer review ratings

These insights can help businesses understand customer value and improve customer retention strategies.

---

### 4. Geographic Analysis

Sales performance can be analyzed across **28 Indian states**.

The dashboard helps identify:

* High-performing states
* Low-performing regions
* Regional sales contribution
* Customer distribution by location

This can support regional marketing and expansion decisions.

---

### 5. Delivery Analysis

The dataset contains three delivery statuses:

* ✅ Delivered
* ⏳ Pending
* ↩️ Returned

The dashboard provides visibility into delivery performance and returned orders, helping identify potential operational issues.

---

### 6. Payment Analysis

Customer payment preferences are analyzed across:

* UPI
* Credit Card
* Debit Card
* Cash on Delivery

This helps understand how customers prefer to complete their purchases.

---

### 7. Customer Review Analysis

Customer satisfaction is analyzed using:

* Review ratings
* Average rating
* Rating distribution
* Review text
* Product-level ratings

This can help identify products with strong or weak customer satisfaction.

---

## 🔍 Key Business Insights

Based on the dataset:

* The dataset contains **₹1.12B+ in total sales** across 15,000 transactions.
* The business serves **7,259 unique customers**.
* **Electronics** has the highest number of transactions among the five categories.
* Customer payment behavior is distributed across UPI, cards, and Cash on Delivery.
* Delivery performance can be evaluated using Delivered, Pending, and Returned orders.
* The average customer rating is approximately **3.04/5**, indicating an opportunity to improve customer satisfaction.
* Geographic analysis across 28 states can help identify high-value markets and potential growth regions.

---

## 🎨 Dashboard Interactivity

The Power BI dashboard includes interactive features such as:

* 🔎 Product filters
* 📅 Date filtering
* 📍 State filtering
* 🛍️ Category filtering
* 💳 Payment method filtering
* 🚚 Delivery status filtering
* ⭐ Rating analysis
* Interactive charts and visualizations
* Cross-filtering between visuals

---

## 📌 Business Questions Answered

This dashboard helps answer questions such as:

1. What is the total revenue generated?
2. How many orders and customers does the business have?
3. Which products generate the highest sales?
4. Which product category performs best?
5. Which states contribute the most revenue?
6. Which payment method is most commonly used?
7. What percentage of orders are delivered, pending, or returned?
8. What is the average customer rating?
9. Which products receive the best customer feedback?
10. Where are potential opportunities for business growth?

---

## 💡 Business Value

The dashboard converts raw transaction-level data into an easy-to-understand analytical report that can support:

* Sales strategy
* Product portfolio decisions
* Customer analysis
* Regional expansion
* Marketing decisions
* Delivery performance monitoring
* Customer experience improvement

---

## 📷 Dashboard Preview

Add screenshots of your Power BI dashboard here.

Example:

```markdown
![Dashboard Overview](images/dashboard-overview.png)
```

You can create an `images` folder in the repository and upload your dashboard screenshots there.

---

## ▶️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/amazon-sales-customer-analytics.git
```

### 2. Open the Power BI File

Open:

```text
Amazon Sales & Customer Analytics Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Explore the Dashboard

Use the available filters, slicers, KPIs, and visualizations to explore the sales and customer data.

---

## 📊 Project Workflow

```text
Raw Excel Dataset
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Interactive Dashboard
        ↓
Business Insights
```

---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Data Visualization
* Power BI
* Power Query
* DAX
* KPI Development
* Business Intelligence
* Customer Analytics
* Sales Analytics
* Geographic Analysis
* Dashboard Design
* Business Insight Generation

---

## 👨‍💻 Author

**Atharv Khumkar**

B.Tech – Data Science

### Skills

`Python` `SQL` `Excel` `Power BI` `Machine Learning` `Data Analytics` `Data Visualization`

---

## ⭐ If You Like This Project

If you found this project useful or interesting, consider giving the repository a **⭐ Star**.

---

## 📜 License

This project is created for **educational and portfolio purposes**.

📁 Amazon-Sales-Customer-Analytics
│
├── 📊 Amazon Sales & Customer Analytics Dashboard.pbix
├── 📄 amazon_sales_2025_INR.xlsx
├── 📁 images
│   ├── dashboard-overview.png
│   ├── sales-analysis.png
│   └── customer-analysis.png
│
└── 📖 README.md
