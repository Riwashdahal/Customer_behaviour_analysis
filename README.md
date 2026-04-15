# 🛍️ Customer Shopping Behavior Analysis

### Turning Raw Transactions into Business Decisions

---

## 🚀 Project Story (Why This Matters)

Businesses often collect large volumes of customer data but struggle to convert it into actionable insights.

In this project, I analyzed **3,900 real-world shopping transactions** to answer a key question:

> **How can we use customer behavior to increase revenue, retention, and smarter marketing?**

This project simulates a real-world **data analyst role**, combining **data cleaning, SQL analysis, and dashboard storytelling**.

---

## 🎯 Business Objectives

* Identify **high-value customer segments**
* Understand **impact of discounts on revenue**
* Analyze **subscription behavior**
* Discover **top-performing products**
* Provide **data-driven marketing strategies**

---

## 📊 Key KPIs (At a Glance)

| KPI                      | Insight                                             |
| ------------------------ | --------------------------------------------------- |
| 💰 Total Revenue         | Strong contribution from specific customer segments |
| 🧑‍🤝‍🧑 Top Segment     | Repeat & loyal customers drive most revenue         |
| 🎯 Discount Impact       | High spenders still use discounts                   |
| 🔁 Subscription Behavior | Repeat buyers more likely to subscribe              |
| 🛍️ Product Performance  | Top products vary significantly by category         |

---

## 🧠 Key Insights (What I Discovered)

### 1. 💸 Discounts ≠ Low Value Customers

Customers using discounts still spend **above average**, indicating an opportunity for **targeted promotions instead of blanket discounts**.

### 2. 🔁 Repeat Customers = Revenue Engine

Customers with multiple previous purchases contribute significantly more revenue and show **higher subscription likelihood**.

### 3. 📦 Product Strategy Matters

Top-performing products differ across categories → businesses should **optimize category-wise promotions**.

### 4. 👥 Customer Segmentation is Critical

Segmenting customers into:

* New
* Returning
* Loyal

…reveals clear differences in spending behavior.

### 5. 📈 Subscription = Growth Lever

Subscribers show strong revenue contribution → opportunity to **convert repeat buyers into subscribers**.

---

## 🛠️ Tech Stack

* **Python (Pandas)** → Data Cleaning & Feature Engineering
* **PostgreSQL** → Data Storage
* **SQL** → Business Analysis
* **Power BI** → Dashboard & Visualization

---

## ⚙️ Data Workflow

### 🔹 Step 1: Data Cleaning (Python)

* Handled missing values using **median imputation by category**
* Standardized column names (snake_case)
* Removed redundant features

### 🔹 Step 2: Feature Engineering

* Created `age_group` using quartiles
* Converted purchase frequency into numeric (`days`)

### 🔹 Step 3: Database Integration

* Loaded cleaned data into PostgreSQL using SQLAlchemy

### 🔹 Step 4: SQL Analysis

Solved 10 real-world business questions including:

* Revenue by gender
* Discount behavior
* Product performance
* Customer segmentation
* Subscription analysis

---

## 📈 Dashboard (Power BI)

The dashboard communicates insights visually:

### Key Visuals:

* Revenue breakdown by segment
* Customer segmentation distribution
* Top products by category
* Subscription vs non-subscription comparison
* Discount usage patterns


---

## 📌 Business Recommendations

✔️ **Target High-Value Discount Users**
→ Offer personalized discounts instead of general campaigns

✔️ **Focus on Repeat Customers**
→ Introduce loyalty programs & subscription incentives

✔️ **Segment-Based Marketing**
→ Tailor campaigns for New vs Loyal customers

✔️ **Optimize Product Strategy**
→ Promote top-performing products per category

✔️ **Increase Subscription Conversion**
→ Target repeat buyers with exclusive benefits

---

## 💡 What Makes This Project Stand Out

* Real-world **business problem solving**
* End-to-end pipeline (**Python → SQL → Dashboard**)
* Strong focus on **decision-making insights (not just analysis)**
* Clean, production-style workflow

---

## 🚀 How to Run

```bash
git clone <your-repo-link>
cd customer-shopping-analysis
pip install pandas sqlalchemy psycopg2
```

Update PostgreSQL credentials in the script:

```python
username = 'postgres'
password = 'your_password'
host = 'localhost'
port = '5432'
database = 'customer_behaviour'
```

Run the script → Load data → Execute SQL queries → Open Power BI dashboard


---





