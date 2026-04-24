# 📊 E-commerce User Behavior & Conversion Analysis

## 📌 Project Overview

This project analyzes user behavior on an e-commerce platform to identify drop-off points in the purchase funnel and evaluate user retention patterns. The goal is to derive actionable insights to improve conversion rates and user engagement.

---

## 🎯 Problem Statement

Analyze user behavior in an e-commerce platform to identify drop-off points in the purchase funnel and provide actionable recommendations to improve conversion rates and user retention.

---

## 📂 Dataset

* Source: E-commerce Events Dataset (Kaggle)
* Records: ~3.5 million user interaction events
* Data includes user actions such as product views, cart additions, and purchases

---

## 🧠 Approach

### 1. Data Understanding

* Analyzed dataset structure and key columns
* Focused on relevant features:

  * `event_time`
  * `event_type`
  * `user_id`
  * `product_id`
  * `price`
* Ignored columns with high missing values (e.g., `category_code`)

---

### 2. Funnel Analysis

* Calculated unique users at each stage:

  * View → Cart → Purchase
* Derived conversion rates between stages

#### 📊 Key Metrics:

* **~23% conversion (View → Cart)**
* **~31% conversion (Cart → Purchase)**

#### 🔍 Insights:

* Significant drop-off at the product view stage
* Stronger conversion once users add items to cart
* Funnel is top-heavy, indicating low product engagement
* High cart abandonment observed

---

### 3. Retention Analysis (Day-Based)

* Since dataset contains one month of data, retention was analyzed on a **day-level basis**
* Measured user return behavior (Day 1, Day 7, etc.)

#### 📊 Key Metrics:

* **~4–5% Day 1 retention**
* **<2% retention by Day 7**

#### 🔍 Insights:

* Sharp drop in user retention after first visit
* Majority of users do not return after initial interaction
* Indicates weak user stickiness and engagement

---

## 💡 Business Recommendations

* Improve product page experience to reduce drop-off at the view stage
* Introduce discounts and offers to encourage cart additions
* Optimize checkout process to reduce cart abandonment
* Implement retargeting strategies (emails/notifications) to improve retention
* Personalize product recommendations to increase repeat engagement

---

## 🧾 Tools & Technologies Used

* Python (Pandas, NumPy)
* SQL (for data extraction and aggregation)
* Matplotlib (for visualization)

---

## 📌 Final Summary

* Significant drop-off (~77%) at product view stage
* Moderate conversion (~31%) from cart to purchase
* Very low user retention (<5% Day 1)
* Overall indicates weak engagement and low repeat usage

---

## 🚀 Outcome

This project demonstrates the ability to:

* Analyze large-scale user behavior data
* Perform funnel and retention analysis
* Generate actionable business insights
* Apply SQL and Python in real-world scenarios

---
## 📂 Dataset

Due to size limitations, the dataset is not included in this repository.

You can download the dataset from the following source:

- https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop

## 📎 Author

Shivam Kumar
