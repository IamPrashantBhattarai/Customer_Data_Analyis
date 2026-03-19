# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data (~3,900 records) across multiple product categories. The goal is to uncover patterns in customer spending, preferences, and engagement to support better business decisions.

---

## 📊 Dataset Summary
- **Total Records:** 3,900
- **Features:** 18

### Key Data Includes:
- **Customer Info:** Age, Gender, Location, Subscription Status
- **Purchase Details:** Item, Category, Purchase Amount, Season, Size, Color
- **Behavior Metrics:** Discount Usage, Promo Codes, Purchase Frequency, Previous Purchases, Ratings, Shipping Type

- Missing values found in the **Review Rating** column

---

## 🧹 Data Cleaning & Preparation (Python)
- Imported the dataset using **pandas**
- Performed initial exploration using `df.info()` and `df.describe()`
- Handled missing values using **median imputation**
- Standardized column names into **snake_case**
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns
- Loaded cleaned data into **PostgreSQL**

---

## 🗄️ SQL Analysis (Business Insights)

Key business questions answered:

1. **Revenue by Gender**
2. **High-Spending Discount Users**
3. **Top 5 Products by Rating**
4. **Shipping Type Comparison**
5. **Subscribers vs Non-Subscribers**
6. **Discount-Dependent Products**
7. **Customer Segmentation (New, Returning, Loyal)**
8. **Top Products per Category**
9. **Repeat Buyers vs Subscription Behavior**
10. **Revenue by Age Group**

---

## 📈 Power BI Dashboard
An interactive dashboard was built to visualize major insights from the dataset.

### Dashboard Highlights:
- Total customers and average purchase amount
- Revenue by category
- Subscription status distribution
- Sales by age group
- Revenue by age group

> Add your Power BI dashboard screenshot here

---

## 💡 Key Insights
- Loyal customers contributed the largest share of total purchases
- Customers using discounts still showed strong spending behavior
- A few product categories generated most of the revenue
- Subscription status had a visible impact on customer behavior

---

## 🚀 Business Recommendations
- Promote subscription plans with exclusive offers
- Build loyalty programs for repeat buyers
- Review discount strategies to balance profit and sales
- Highlight top-selling and top-rated products in campaigns
- Use targeted marketing for high-value customer groups

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **PostgreSQL**
- **Power BI**

---

## 📂 Project Structure
```bash
├── data/
├── notebooks/
├── sql/
├── dashboard/
└── README.md
