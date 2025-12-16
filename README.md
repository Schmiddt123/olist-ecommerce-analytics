# Olist E-Commerce Analytics Project
**Note**: Power BI dashboard file (.pbix) not included due to size. Screenshots demonstrate full functionality.

🚧 **Project status:** In active development (12.2025)

## 📍 Project Roadmap
- [x] Load raw data  
- [x] Create SQL schema (PK/FK, constraints)  
- [x] Build ERD diagram  
- [x] Clean and transform data  
- [ ] Analytical SQL queries (sales, delivery performance, reviews)   
- [x] Power BI dashboard

      # Olist E-Commerce Analytics Project

## 📊 Overview

Analysis of Brazilian e-commerce data from Olist (2016-2018) covering **$15.84M in revenue** and **99,441 orders**.

## 🎯 Key Insights

- Revenue decline in September was **volume-driven, not price-driven**
- **São Paulo dominates** with 37.38% of total revenue
- **91.89%** on-time delivery rate with 12-day average delivery time
- **Credit cards** account for majority of transactions
- Average On Time delivery review score: **4.29/5**

## 📈 Dashboard

Interactive Power BI dashboard with 3 pages:

1. **Revenue & Orders** - Monthly trends, top categories, order values
2. **Seller Performance** - Geographic distribution, delivery metrics, review scores
3. **Customer Behavior** - Payment methods analysis


## 🗂️ Data Model

Star schema with 9 tables: orders, order_items, order_payments, order_reviews, customers, sellers, products, categories, geolocation.

## 🛠️ Tools

- Microsoft Power BI
- Data Source: [Olist Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)



