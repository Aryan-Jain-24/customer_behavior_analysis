# Customer Shopping Behavior Analysis

A complete data analytics project focused on understanding customer purchasing patterns, product preferences, and subscription behavior using Python, PostgreSQL, and Power BI. This project transforms raw transactional data into actionable business insights through data cleaning, SQL analysis, and interactive visualizations.

---

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective was to uncover insights into:

* Customer spending habits
* Product performance
* Subscription behavior
* Discount effectiveness
* Customer segmentation

The project workflow included:

1. Data Cleaning & Feature Engineering using Python
2. SQL-based Business Analysis using PostgreSQL
3. Interactive Dashboard Development using Power BI

---

## 🛠️ Tech Stack

* **Python**

  * Pandas
  * NumPy
* **PostgreSQL**
* **Power BI**
* **Jupyter Notebook / VS Code**

---

## 📂 Dataset Information

* **Rows:** 3,900
* **Columns:** 18

### Key Features

* Customer demographics (Age, Gender, Location)
* Purchase details (Item, Category, Amount, Season)
* Shopping behavior (Discounts, Reviews, Frequency)
* Subscription status
* Shipping preferences

### Data Cleaning Performed

* Handled missing values in `review_rating`
* Standardized column names to snake_case
* Removed redundant columns
* Created derived columns such as:

  * `age_group`
  * `purchase_frequency_days`

---

## 🔍 Exploratory Data Analysis (Python)

### Tasks Performed

* Dataset inspection using `.info()` and `.describe()`
* Missing value analysis
* Feature engineering
* Customer age segmentation
* Data consistency checks
* PostgreSQL database integration

---

## 🗄️ SQL Business Analysis

Performed multiple business-focused SQL analyses in PostgreSQL:

### Key Insights

#### 1. Revenue by Gender

Compared total revenue contribution between male and female customers.

#### 2. High-Spending Discount Users

Identified customers who used discounts yet spent above-average purchase amounts.

#### 3. Top Rated Products

Found products with the highest average review ratings.

#### 4. Shipping Type Comparison

Compared spending patterns between Standard and Express shipping users.

#### 5. Subscriber vs Non-Subscriber Analysis

Analyzed customer count, average spend, and total revenue by subscription status.

#### 6. Discount-Dependent Products

Identified products most frequently purchased with discounts.

#### 7. Customer Segmentation

Segmented customers into:

* New
* Returning
* Loyal

#### 8. Top Products per Category

Ranked the top-selling products in each category.

#### 9. Repeat Buyers & Subscriptions

Checked whether repeat buyers are more likely to subscribe.

#### 10. Revenue by Age Group

Calculated total revenue contribution across different age groups.

---

## 📊 Power BI Dashboard

Built an interactive dashboard to visualize:

* Revenue trends
* Sales by category
* Customer segmentation
* Subscription distribution
* Revenue by age group
* Product category performance

### Dashboard Features

* Interactive filters
* KPI cards
* Bar charts
* Pie charts
* Revenue analysis visuals

---

## 💡 Business Recommendations

* Improve subscription conversion through exclusive offers
* Build loyalty programs for repeat customers
* Optimize discount strategies
* Promote high-rated products in marketing campaigns
* Focus marketing on high-revenue customer segments

---

## 📸 Project Preview

Dashboard and SQL output screenshots are included in the project report.

---

## 🚀 Future Improvements

* Add predictive analytics for customer churn
* Implement recommendation systems
* Deploy dashboard online
* Automate ETL pipeline

---

## 📁 Project File

Detailed project documentation: 

---

## 👤 Author

Aryan Jain
Aspiring Business Analyst / Product Management Enthusiast
Passionate about Data Analytics, SQL, and AI-powered solutions.
