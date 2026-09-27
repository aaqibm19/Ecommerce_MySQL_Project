# 📊 MySQL 8.0 Advanced Data Analytics Project

An end-to-end SQL analytics project analyzing e-commerce transactional data using **MySQL 8.0+**. This repository contains 26 real-world business queries focusing on key analytical concepts including **Complex JOINs**, **Window Functions**, **Common Table Expressions (CTEs)**, and **Subqueries**.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Database Schema](#-database-schema)
- [Key Analytical Concepts Covered](#-key-analytical-concepts-covered)
- [Query Directory](#-query-directory)
- [Getting Started & Installation](#-getting-started--installation)
- [Key Business Insights](#-key-business-insights)

---

## 🎯 Project Overview

This project simulates an e-commerce platform's data layer to solve critical business problems such as:
- **Customer Segmentation:** Classifying customers based on spend thresholds (High, Medium, Low Value).
- **Revenue Performance:** Tracking product-type margins, order values, and running monthly totals.
- **Behavioral Analytics:** Measuring repeat order cadence, days between purchases (`LAG`), and customer activity trends (`FIRST_VALUE`, `LAST_VALUE`).
- **Performance Benchmarking:** Filtering orders and products that perform above monthly or cohort averages.

**Core Formula Standard:**
$$\text{Revenue} = \text{quantity} \times \text{unit\_price}$$

---

## 🗄️ Database Schema

The database consists of 4 core tables modeling customers, orders, products, and order line items:
