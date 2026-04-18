# 🚀 Smart Employee Project Analytics System

## 📌 Overview

This project is an end-to-end data analytics solution built using **Python, Pandas, and NumPy** to analyze project and employee data. It focuses on data cleaning, transformation, integration, and applying business logic to generate actionable insights. The project simulates real-world scenarios where multiple datasets are combined to evaluate employee performance and project outcomes.

---

## 🎯 Objectives

* Clean and preprocess raw data
* Handle missing values using a running average technique
* Merge multiple datasets for unified analysis
* Apply business rules to evaluate performance
* Generate insights such as bonuses, designation updates, and cost analysis

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy

---

## 📂 Datasets Used

* **Project Data** – Contains project details, cost, and status
* **Employee Data** – Includes employee demographics
* **Seniority Data** – Defines employee designation levels

---

## ⚙️ Key Features

### 🔹 Data Cleaning & Preprocessing

* Handled missing values using **running average logic**
* Split and transformed columns for better usability

### 🔹 Data Integration

* Merged multiple datasets using common keys (`ID`)
* Created a unified dataset for analysis

### 🔹 Business Logic Implementation

* 💰 Calculated **5% bonus** for completed projects
* 📉 Adjusted designation levels for failed projects
* 📈 Promoted employees based on age criteria
* 🧾 Added titles (Mr./Mrs.) based on gender

### 🔹 Data Analysis

* Calculated **total project cost per employee**
* Filtered data based on conditions (e.g., city-based filtering)

---

## 📊 Sample Insights

* Improved understanding of employee contribution across projects
* Identified cost distribution and high-value contributors
* Enabled performance-based evaluation using project outcomes

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:
   ```
   pip install pandas numpy
   ```
3. Run the Python script or Jupyter Notebook
