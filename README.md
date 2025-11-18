# 📊 E‑Commerce Customer Behavior Analysis

## 📑 Project Overview
This project explores an **E‑Commerce Customer Behavior Dataset** with 5,000+ records and 18 features.  
The dataset captures customer demographics, purchase details, browsing behavior, payment preferences, delivery times, and satisfaction ratings.  
The goal is to perform **end‑to‑end exploratory data analysis (EDA)** — from cleaning and wrangling to visualization and insights — without machine learning.

---

## 🛒 Dataset Features
- **Order details**: `order_id`, `customer_id`, `order_date`, `product_category`, `unit_price`, `quantity`, `discount_amount`, `total_amount`
- **Customer demographics**: `age`, `gender`, `city`
- **Behavioral metrics**: `session_duration_minutes`, `pages_viewed`, `is_returning_customer`
- **Transaction info**: `payment_method`, `device_type`
- **Delivery & satisfaction**: `delivery_time_days`, `customer_rating`

---

## 🎯 Analysis Performed
1. **Data Cleaning & Preparation**
   - Standardized column names, handled missing values, created time features.
2. **Sales Analysis**
   - Monthly revenue trends, revenue by product category, discount impact.
3. **Customer Demographics**
   - Age distribution, gender‑based revenue, top cities by sales.
4. **Behavioral Insights**
   - Session duration vs order value, pages viewed vs conversion, returning vs new customers.
5. **Payment & Device Trends**
   - Popular payment methods, mobile vs desktop usage.
6. **Delivery & Ratings**
   - Delivery time distribution, correlation with customer ratings, category‑wise satisfaction.
7. **Correlation Heatmap**
   - Relationships between numeric features (discounts, revenue, ratings).

---

## 📊 Tools & Libraries
- **Python** → Pandas, NumPy  
- **Visualization** → Seaborn, Matplotlib, Plotly Express  
- **Environment** → Jupyter Notebook  

---

## ✨ Key Insights
- Electronics and Home & Garden drive the highest revenue.  
- Returning customers spend more per order than new customers.  
- Longer browsing sessions and more pages viewed correlate with higher order values.  
- Faster delivery times lead to better customer ratings.  
- Mobile devices dominate purchases, with credit cards as the most common payment method.  

---

## 🚀 Conclusion
This project demonstrates the **data analyst workflow**: cleaning, exploration, visualization, and storytelling.  
It highlights how raw e‑commerce data can be transformed into **business insights** that inform marketing, logistics, and customer engagement strategies.

---

## 📂 Repository Structure
Ecommerce-Customer-Behavior-Analysis/
│
├── data/                     # Raw and cleaned datasets
│   ├── ecommerce_customer_behavior_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/                # Jupyter notebooks with step-by-step analysis
│   ├── 01_data_cleaning.ipynb
│   ├── 02_sales_analysis.ipynb
│   ├── 03_customer_demographics.ipynb
│   ├── 04_behavioral_analysis.ipynb
│   ├── 05_payment_device_trends.ipynb
│   ├── 06_delivery_ratings.ipynb
│   └── 07_summary_conclusions.ipynb
│
├── visuals/                  # Saved charts and plots
│   ├── monthly_revenue.png
│   ├── category_revenue.png
│   ├── age_distribution.png
│   └── correlation_heatmap.png
│
├── scripts/                  # Python scripts for reusable functions
│   ├── data_cleaning.py
│   ├── visualization.py
│   └── utils.py
│
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── LICENSE                   # License file (optional)
