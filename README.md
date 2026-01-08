# Instacart Market Basket Analysis
## Author
Raunak Sharma  


## Overview
This project analyzes customer purchasing behavior using the **Instacart Market Basket Analysis** dataset to uncover product affinities, frequently co-purchased items, and shopping patterns. The goal is to demonstrate how transactional retail data can be transformed into actionable insights for **cross-selling, recommendations, and inventory optimization**.

The analysis focuses on understanding *what products customers buy together* and *how often*, using association rule mining techniques.

---

## Instacart Dashboard

🔗 Live dashboard: https://lookerstudio.google.com/reporting/71e8535e-f2af-408a-84d9-a40ef38c1016

![Dashboard Overview](Instacart_market_basket_analysis.png)



## Objectives
- Explore large-scale transactional retail data
- Identify frequently purchased items and item combinations
- Generate association rules using market basket analysis
- Interpret **support, confidence, and lift** metrics for business decision-making
- Demonstrate practical applications in e-commerce and retail analytics

---

## Dataset
- **Source:** Instacart Online Grocery Shopping Dataset (public dataset)
- **Records:** Millions of orders and order-product combinations
- **Granularity:** Product-level transaction data
- **Key Tables Used:**
  - Orders
  - Order–Product mappings
  - Product metadata (aisle, department)

---

## Tech Stack
- **Python**
- **Pandas & NumPy** – data manipulation
- **Matplotlib / Seaborn** – exploratory visualizations
- **mlxtend** – Apriori algorithm and association rule mining
- **Jupyter Notebook** – analysis and presentation

---

## Methodology

### 1. Data Preparation
- Filtered and cleaned transactional data
- Transformed order-level data into a **basket format**
- Reduced sparsity by focusing on frequently purchased products

### 2. Exploratory Data Analysis (EDA)
- Most frequently purchased products
- Order size distributions
- Category-level purchasing trends

### 3. Market Basket Analysis
- Applied the **Apriori algorithm** to identify frequent itemsets
- Generated association rules based on:
  - **Support** – how often items appear together
  - **Confidence** – likelihood of purchasing item B given item A
  - **Lift** – strength of association beyond random chance

---

## Key Insights
- Certain staple products (e.g., produce and dairy items) appear consistently across baskets
- Strong co-purchase relationships exist between complementary products
- High-lift rules reveal opportunities for:
  - Product bundling
  - Cross-selling strategies
  - Personalized recommendations

---

## Business Applications
- **Recommendation systems:** Suggest related products at checkout
- **Marketing:** Targeted promotions for frequently co-purchased items
- **Inventory management:** Anticipate demand for complementary products
- **Store layout optimization:** Place associated products closer together

---

## Key Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Association Rule Mining (Apriori)
- Business interpretation of analytical metrics
- Handling large transactional datasets
- Translating data insights into actionable recommendations

---

 
