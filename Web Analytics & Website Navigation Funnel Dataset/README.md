# Web Analytics & E-Commerce Funnel Dataset  

## Overview  

This dataset contains **simulated e-commerce and web analytics data** designed to analyze **user behavior, product performance, and revenue flow** across an online business.  

It captures the full journey from **website session → pageviews → orders → order items → refunds**, making it ideal for **end-to-end funnel analysis**.  

---

## Context  

Understanding user behavior and conversion funnels is critical in any digital business. This dataset enables analysis of:  

- How users **arrive on the website** (traffic sources, campaigns)  
- How they **navigate through pages**  
- What drives **purchases and revenue**  
- Where **drop-offs and refunds** occur  

This is especially useful for **data analysts and aspiring data scientists** working on **real-world business problems** like conversion optimization and revenue analysis.  

---

## Dataset Description  

The dataset consists of **multiple related tables** representing different stages of the e-commerce funnel:  

---

### 🧾 **orders**  

| Column Name | Description |
|------------|------------|
| **order_id** | Unique identifier for each order |
| **created_at** | Timestamp when the order was placed |
| **website_session_id** | Session associated with the order |
| **user_id** | Unique user identifier |
| **primary_product_id** | Main product in the order |
| **items_purchased** | Total number of items purchased |
| **price_usd** | Total revenue from the order |
| **cogs_usd** | Cost of goods sold |

---

### 📦 **order_items**  

| Column Name | Description |
|------------|------------|
| **order_item_id** | Unique identifier for each item |
| **created_at** | Timestamp when the item was added |
| **order_id** | Associated order ID |
| **product_id** | Product identifier |
| **is_primary_item** | Indicates if it's the main item (`1 = Yes`, `0 = No`) |
| **price_usd** | Price of the item |
| **cogs_usd** | Cost of the item |

---

### 💸 **order_item_refunds**  

| Column Name | Description |
|------------|------------|
| **order_item_refund_id** | Unique refund identifier |
| **created_at** | Timestamp of refund |
| **order_item_id** | Refunded item ID |
| **order_id** | Associated order |
| **refund_amount_usd** | Refund amount |

---

### 🛍️ **products**  

| Column Name | Description |
|------------|------------|
| **product_id** | Unique product identifier |
| **created_at** | Product creation date |
| **product_name** | Name of the product |

---

### 🌐 **website_sessions**  

| Column Name | Description |
|------------|------------|
| **website_session_id** | Unique session identifier |
| **created_at** | Session start timestamp |
| **user_id** | User identifier |
| **is_repeat_session** | Indicates returning user (`1 = Yes`, `0 = No`) |
| **utm_source** | Traffic source (e.g., Google, Facebook) |
| **utm_campaign** | Marketing campaign name |
| **utm_content** | Ad/content variation |
| **device_type** | Device used (`Desktop`, `Mobile`) |
| **http_referer** | Referring website |

---

### 📄 **website_pageviews**  

| Column Name | Description |
|------------|------------|
| **website_pageview_id** | Unique pageview identifier |
| **created_at** | Timestamp of pageview |
| **website_session_id** | Associated session |
| **pageview_url** | URL visited |

---

## How This Dataset Can Be Used  

This dataset supports a wide range of **analytics and data science use cases**:  

### 1️⃣ Funnel Analysis  
- Track user journey from **session → pageview → purchase**  
- Identify **conversion rates** and drop-off points  

### 2️⃣ Marketing Performance Analysis  
- Evaluate performance of **UTM campaigns and traffic sources**  
- Compare **conversion rates by channel**  

### 3️⃣ Product & Revenue Analysis  
- Identify **top-performing products**  
- Analyze **profit margins (Revenue vs COGS)**  

### 4️⃣ Customer Behavior Analysis  
- Compare **new vs returning users**  
- Analyze behavior across **device types**  

### 5️⃣ Refund & Loss Analysis  
- Track **refund rates and patterns**  
- Identify products with **high return rates**  

---

## Future Scope  

✅ Add **customer segmentation features**  
✅ Integrate with **marketing spend data** for ROI analysis  
✅ Build **cohort retention analysis**  
✅ Develop **advanced funnel visualization dashboards**  

---

## How to Access & Use  

🔹 Available in **CSV format**  
🔹 Can be used with **SQL, Excel, Power BI, Python**  
🔹 Ideal for **portfolio projects and case studies**  

---

## Author  

**Tanvir Taushif** - Data Analyst & Data Science Enthusiast  
📩 Contact: [LinkedIn](https://www.linkedin.com/in/tanvir-taushif-751044204/)  

---

## License & Usage  

This dataset is intended for **educational and portfolio purposes**.  
Please provide proper attribution if used in public work.  

---

#DataAnalytics #WebAnalytics #Ecommerce #FunnelAnalysis #SQL #PowerBI #Python #DataScience
