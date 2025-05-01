# 📊 Free Datasets for Learning – Banking & Customer Analytics

This repository contains a curated collection of **synthetic banking datasets** designed for educational and project-based learning. The data models realistic behavior across banking operations including customer activity, digital usage, loan performance, and transactions with built-in seasonality and behavioral trends.

---

## 📦 Datasets Included

| File Name                        | Description                                      |
|----------------------------------|--------------------------------------------------|
| `Dim_Customer.csv`              | Customer demographic details                     |
| `Dim_Account.csv`               | Account information, open/close details          |
| `Dim_Branch.csv`                | Branch metadata                                  |
| `Dim_Product.csv`               | Bank product listing                             |
| `Fact_Transactions.csv`         | Transaction records with fraud pattern simulation|
| `Fact_CustomerInteraction.csv`  | Customer service and interaction logs            |
| `Fact_DigitalUsage.csv`         | Digital banking usage activity                   |
| `Fact_LoanPerformance.csv`      | Loan disbursal, repayment, default information   |
| `Digital Customer Score Title.xlsx` | Feature logic for digital engagement scoring |

---

## 💡 How to Use This Dataset

This dataset has been designed to reflect **realistic banking behavior** with seasonal and behavioral trends for hands-on learning.

### 🔍 Analytical Use Cases

- **Descriptive Analysis**: Identify top branches, customer trends, income distribution.
- **Time Series Analysis**: Detect seasonality in transaction and digital usage.
- **Cohort & Funnel Analysis**: Analyze digital onboarding or loan repayment behavior.

### 🧠 Machine Learning & Data Projects

- 🎯 **Customer Segmentation** (K-Means, DBSCAN)
- 💳 **Fraud Detection** using anomalies in transactions
- 🧾 **Loan Default Prediction** using repayment + demographics
- 📱 **Digital Engagement Modeling** (classification or scoring)
- 📦 **Product Recommendation** based on user patterns

### 📊 Business Intelligence Dashboards

- Power BI or Tableau dashboards:
  - Branch performance
  - Product-wise customer counts
  - Seasonal revenue patterns

---

### 📈 Realistic Data Features

- ✅ **Seasonality**: Spikes in the 1st week of months & during major festivals.
- ✅ **Behavioral Patterns**: Engagement & satisfaction varies across customer groups.
- ✅ **Dormancy & Fraud Simulation**: Used for fraud model prototyping and churn.

---

### 📋 Dataset Summary (Row Counts)

| Dataset                        | Rows     |
|--------------------------------|----------|
| `Dim_Customer.csv`             | 5,000    |
| `Dim_Account.csv`              | 5,000    |
| `Dim_Branch.csv`               | 13       |
| `Dim_Product.csv`              | 10       |
| `Fact_Transactions.csv`        | 110,351  |
| `Fact_CustomerInteraction.csv` | 12,000   |
| `Fact_DigitalUsage.csv`        | 49,849   |
| `Fact_LoanPerformance.csv`     | 3,190    |

---

## 🧾 Dataset Schema & Column Descriptions

### 🧑‍💼 `Dim_Customer.csv`
| Column Name     |
|-----------------|
| Customer_ID     |
| Customer_Name   |
| Date_of_Birth   |
| Gender          |
| Occupation      |
| Income          |
| Marital_Status  |
| Region          |

---

### 🏦 `Dim_Account.csv`
| Column Name     |
|-----------------|
| Account_ID      |
| Customer_ID     |
| Account_Type    |
| Account_Status  |
| Open_Date       |
| Close_Date      |

---

### 🏢 `Dim_Branch.csv`
| Column Name     |
|-----------------|
| Branch_ID       |
| Branch_Name     |
| Region          |
| Type            |

---

### 📦 `Dim_Product.csv`
| Column Name     |
|-----------------|
| Product_ID      |
| Product_Name    |
| Launch_Date     |
| Status          |

---

### 💬 `Fact_CustomerInteraction.csv`
| Column Name         |
|---------------------|
| Interaction_ID      |
| Customer_ID         |
| Date                |
| Channel             |
| Issue_Type          |
| Outcome             |
| Satisfaction_Score  |

---

### 🌐 `Fact_DigitalUsage.csv`
| Column Name             |
|-------------------------|
| Session_ID              |
| Account_ID              |
| Customer_ID             |
| Date                    |
| Device_Type             |
| Feature_Used            |
| Time_Spent              |
| Transactions_Completed  |

---

### 🏛️ `Fact_LoanPerformance.csv`
| Column Name        |
|--------------------|
| Loan_ID            |
| Customer_ID        |
| Account_ID         |
| Product_ID         |
| Date_Origination   |
| Date_Closure       |
| Loan_Amount        |
| Interest_Rate      |
| Default_Flag       |
| Recovery_Amount    |

---

### 💸 `Fact_Transactions.csv`
| Column Name         |
|---------------------|
| Transaction_ID      |
| Account_ID          |
| Customer_ID         |
| Product_ID          |
| Date                |
| Branch_ID           |
| Amount              |
| Channel             |
| Transaction_Type    |
| Fee_Charged         |
| Transaction_Status  |
| Unnamed: 11         |
| Unnamed: 12         |

> ⚠️ **Note**: `Unnamed: 11` and `Unnamed: 12` are empty columns — remove during cleaning.

---

### 📘 `Digital Customer Score Title.xlsx`

Includes:
- Feature weights and definitions for scoring customer digital behavior
- Used in engagement scoring or segmentation models

---

## 🛠️ Tools Recommended

- **Languages**: Python, SQL
- **Libraries**: pandas, scikit-learn, XGBoost, matplotlib, seaborn
- **Platforms**: Jupyter Notebook, Google Colab, Kaggle
- **BI Tools**: Power BI, Tableau, Streamlit

---

## 📘 License

These datasets are **synthetic and free to use** for academic, personal, or research projects. No real customer data is included.

---

## 🙋‍♂️ Contributing

Found a bug? Want to suggest a new dataset?  
Open an issue or create a pull request.

---

## 📩 Contact

Maintained by [Tanvir Taushif](https://github.com/Tanvir-Taushif)  
Feel free to reach out via GitHub for questions or suggestions.

