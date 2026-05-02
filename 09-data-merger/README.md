# 🔗 Relational Data Merger (Pandas Project 9)

This project is part of the **Pandas Mastery Project Series**, focusing on working with relational datasets and performing real-world data analysis.

---

## 🚀 Overview

This project combines multiple relational datasets from a Brazilian e-commerce platform to create a unified dataset for analysis. It demonstrates how to join interconnected tables, enrich data, and extract meaningful business insights.

---

## 📊 Dataset

**Brazilian E-Commerce Dataset (Olist)**
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data

### 📁 Files Used

* `olist_orders_dataset.csv` → Order-level information
* `olist_customers_dataset.csv` → Customer details and location
* `olist_order_items_dataset.csv` → Product-level order data
* `olist_products_dataset.csv` → Product metadata
* `olist_order_payments_dataset.csv` → Payment information
* `product_category_name_translation.csv` → Category name translation (Portuguese → English)

---

## 🔍 Features

* Performing multi-table joins using common keys (`order_id`, `customer_id`, `product_id`)
* Building a unified dataset from relational data sources
* Enriching product data using category translation
* Analyzing revenue distribution across customer regions
* Identifying top-performing product categories
* Exploring payment behavior and transaction patterns
* Extracting customer-level insights from transactional data

---

## 📁 Project Structure

```id="p9rf1"
09-relational-data-merger/
│
├── data_merger.ipynb
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── product_category_name_translation.csv
│   └── final_merged_data.csv
└── README.md
```

---

## ▶️ How to Run

1. Navigate to project folder:

   ```
   cd 09-relational-data-merger
   ```

2. Launch Jupyter Notebook:

   ```
   jupyter notebook
   ```

3. Run `data_merger.ipynb`

---

## 🎯 Learning Outcome

* Understanding relational data structures
* Performing multi-table joins in Pandas
* Enriching datasets for better analysis
* Extracting business insights from transactional data
* Working with real-world datasets

---

📌 This project demonstrates how to transform relational data into a unified dataset and perform meaningful business analysis using Pandas.
