# Dream Supershop Dataset

Welcome to the **Dream Supershop Dataset**! This dataset is designed to simulate real-world sales and customer data for a fictional retail business. It provides over 12,000 sales records, 200 customer records, and detailed product and category data. This dataset offers a great opportunity to practice various data analysis techniques, including data preprocessing, data modeling, and visualization.

## Dataset Overview

The **Dream Supershop Dataset** consists of six Excel files that contain information on customers, products, categories, subcategories, and sales. The dataset simulates a real-world retail environment and can be used to practice skills like data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling.

### **Dataset Files:**
1. **Dream_Super_Shop_Customer_Data.xlsx**
   - Contains information about customers, including customer IDs, names, birth dates, marital status, gender, occupation, branch, and whether they are premium customers.
   - **Fields/Columns:**
     - CustomerID
     - CustomerName
     - BirthDate
     - MaritalStatus
     - Gender
     - Occupation
     - Branch
     - PremiumCustomer

2. **Dream_Super_Shop_Product_Categories_Data.xlsx**
   - Contains details about product categories.
   - **Fields/Columns:**
     - CategoryKey
     - CategoryName

3. **Dream_Super_Shop_Product_Data.xlsx**
   - Contains details about individual products, including product IDs, subcategory associations, names, costs, and prices.
   - **Fields/Columns:**
     - ProductKey
     - SubCategoryKey
     - ProductName
     - UnitCost
     - UnitPrice

4. **Dream_Super_Shop_Product_Subcategories_Data.xlsx**
   - Contains information about product subcategories.
   - **Fields/Columns:**
     - SubCategoryKey
     - SubCategoryName
     - CategoryKey

5. **Dream_Super_Shop_Sales_Data.xlsx**
   - Contains sales transaction records, including sales IDs, customer IDs, product IDs, quantities, dates, branches, and payment methods.
   - **Fields/Columns:**
     - SalesID
     - CustomerID
     - ProductID
     - Quantity
     - Date
     - Branch
     - PaymentMethod
6. **Calender_lookup_table.xlsx**
   - Contains date from May 01, 2024 to November 30, 2024
   - **Fields/Columns:**
     - Date

### **Dataset Size:**
- **Sales Records:** Over 12,000 sales records.
- **Customers:** 200 unique customer records.
- **Products:** Detailed product and category information, including product IDs, names, prices, and stock levels.

## Purpose of the Dataset:
This dataset is ideal for:
- **Data Preprocessing:** Cleaning and transforming raw data into a usable format for analysis and modeling.
- **Exploratory Data Analysis (EDA):** Exploring the relationships between sales, customers, and products.
- **Data Modeling:** Building models to predict sales, customer behavior, or inventory management.
- **Data Visualization:** Creating interactive visualizations to understand sales trends, customer segmentation, and product performance.

## How to Use This Dataset

1. **Download the dataset:** Download the Excel files to get started.
2. **Data Exploration:** Use the dataset to explore customer demographics, product performance, and sales trends.
3. **Data Preprocessing:** Clean the data by handling missing values, correcting data types, and normalizing data.
4. **Data Modeling:** Apply machine learning models to predict sales, customer preferences, or inventory needs.
5. **Visualization:** Use tools like Python (Matplotlib, Seaborn), Tableau, or Power BI to create visualizations that provide insights into sales performance and customer behavior.

## Example Use Cases

- **Sales Trend Analysis:** Analyze sales trends over time and identify peak sales periods.
- **Customer Segmentation:** Segment customers based on demographics and purchase history to identify target groups.
- **Product Performance:** Analyze which products are performing well and which categories need attention.
- **Predictive Modeling:** Build predictive models to forecast future sales based on historical data.

## Dataset License

This dataset is publicly available for educational and non-commercial use. You can use the data for personal projects, analysis, or research. Please credit this repository when using the dataset in your projects.
