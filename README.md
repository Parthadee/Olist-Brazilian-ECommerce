# 🛒 Brazilian E-Commerce Olist Store

![Dataset Cover](https://github.com/mlnayusuf24/Olist-Store/blob/main/images/dataset-cover.png)

---

## 📌 Introduction

Olist is an e-commerce platform that brings together many different sellers. Through Olist, sellers can sell their products to their customers, which will be delivered by Olist's logistics partners. Olist data provides on Kaggle with information on nearly 100 thousand orders from 2016 to 2018, organized into many different files, including data about: customers, orders, products, payments, sellers, reviews , geolocation,etc. Below is a diagram of Olist's database divided into corresponding files.

The dataset, available on Kaggle, contains approximately **100,000 orders from 2016 to 2018**, organized into multiple relational tables covering customers, orders, products, payments, sellers, reviews, and geolocation data.

---

## 🎯 Problem Statement

E-commerce platforms rely heavily on **personalization, recommendation systems, and data-driven decision-making** to improve customer experience and business performance.

This project focuses on building a **Market Basket Analysis / Recommendation System** that can:

- Understand user-item interactions based on historical purchase behavior
- Predict user preferences for products
- Improve product discovery and personalization
- Enhance customer experience through intelligent recommendations

In real-world applications, such systems are widely used in platforms like Amazon and Netflix to increase engagement and sales.

---

## 🎯 Objective

The objective of this project is to design and implement an end-to-end **Machine Learning pipeline** for a recommendation system, covering:

- Data collection and integration from multiple relational datasets  
- Exploratory Data Analysis (EDA) to extract meaningful insights  
- Feature engineering for model readiness  
- Model training and selection  
- Evaluation using appropriate metrics  
- Deployment-ready architecture for real-world usage  

---

## 📊 About the Dataset

This dataset represents real commercial transactions from Brazilian marketplaces between 2016 and 2018. It provides a multi-dimensional view of e-commerce operations, including:

- Order lifecycle and status  
- Payment and freight performance  
- Customer demographics and location  
- Product attributes  
- Seller information  
- Customer reviews  

A geolocation dataset is also included, mapping Brazilian zip codes to latitude and longitude coordinates.

📥 **Dataset Source:**  
[Kaggle - Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🗂️ Dataset Structure

The dataset consists of multiple relational tables:

- **olist_customers_dataset** – Customer information and location  
- **olist_geolocation_dataset** – Zip code to latitude/longitude mapping  
- **olist_order_items_dataset** – Items purchased in each order  
- **olist_order_payments_dataset** – Payment details per order  
- **olist_orders_dataset** – Core order-level dataset  
- **olist_products_dataset** – Product metadata  
- **olist_sellers_dataset** – Seller information and location  
- **product_category_name_translation** – Product category translation (Portuguese → English)

---

## 🧾 Data Sources

![Database Diagram](https://github.com/ductransponster/Olist-Brazilian-Ecommerce/blob/main/image/database_diagram.png)

---

## 🧩 Relational Schema

<img src="https://github.com/Parthadee/Olist-Brazilian-ECommerce/blob/fbde45d59282b35b7a76c8de0c3701a14804d2d9/output/Relational%20Schema.png" alt="Relational Schema" width="700"/>

---

## 📈 Dataset Overview

- **Total Orders:** ~100,000  
- **Time Period:** 2016 – 2018  
- **Coverage:** Multiple Brazilian marketplaces  
- **Data Privacy:** Anonymized customer and seller information  

---

## 🔁 Flow Explanation

The project follows a standard end-to-end machine learning workflow:

### 1. Data Wrangling
Cleaning, merging, and structuring raw datasets into an analysis-ready format.

### 2. Exploratory Data Analysis (EDA)
Understanding patterns, trends, and relationships using statistical and visual analysis.

### 3. Modeling
Training machine learning models to learn patterns from historical data and make predictions.

### 4. Model Evaluation
Evaluating model performance using train-test split and relevant metrics.

### 5. Containerization (Docker)
Packaging the application into a Docker container for portability and reproducibility.

### 6. Deployment
Deploying the trained model into a production environment for real-world predictions and business use.

---

## 🎯 Use Cases

This dataset supports multiple real-world applications:

- Exploratory Data Analysis (EDA)
- Customer behavior analysis
- E-commerce sales analysis
- Geographic and logistics optimization
- Recommendation systems
- Machine learning models (review prediction, delivery prediction, etc.)

---

## 📌 Notes

- All datasets are relational and must be joined using appropriate keys.
- Each notebook in this repository focuses on a specific analytical or modeling task.
- Not all datasets are used in every analysis.

---

## 🙌 Acknowledgements

Special thanks to **Olist**, a Brazilian e-commerce platform, for making this dataset publicly available on Kaggle.
