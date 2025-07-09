# 🛒 Customer Purchase Behavior Analysis System

This SQL project analyzes customer purchase behavior across products, categories, and cities using a simple relational schema. It helps understand customer spending, product popularity, and location-wise sales — ideal for SQL beginners and data analysts.

## 📁 Tables Used

**customers**: Stores customer details  
- customer_id (INT, PRIMARY KEY)  
- customer_name (VARCHAR)  
- city (VARCHAR)  
- registration_date (DATE)

**products**: Stores product information  
- product_id (INT, PRIMARY KEY)  
- product_name (VARCHAR)  
- category (VARCHAR)  
- price (DECIMAL)

**transactions**: Records each purchase  
- transaction_id (INT, PRIMARY KEY, AUTO_INCREMENT)  
- customer_id (INT, FOREIGN KEY → customers)  
- product_id (INT, FOREIGN KEY → products)  
- quantity (INT)  
- transaction_date (DATE)

## 📦 Sample Data Overview

- 4 customers (from Chennai, Bangalore, Delhi, Hyderabad)  
- 5 products (covering categories like Pulses, Grains, Dairy, Oil, Personal Care)  
- 7 transactions

