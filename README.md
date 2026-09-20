# 📊 Excel Data Exploration & Analysis

## 📌 Project Overview

This project is part of my **Data Analytics learning journey** and focuses on performing basic **data exploration and analysis using Microsoft Excel**.

The objective of this assignment is to analyze a product dataset using Excel formulas and functions, summarize important information, apply logical and conditional calculations, and extract useful information from Product IDs.

This project demonstrates my foundational skills in **Excel and Data Analysis** as I build my portfolio toward a career as a **Data Analyst**.

---

## 🎯 Problem Statement

The dataset contains information about different products, including:

* Product ID
* Product Name
* Brand Name
* Quantity
* Category
* Price

The task is to explore the dataset using Excel functions and perform calculations, categorization, conditional analysis, and text extraction.

---

## 🗂️ Dataset

**Dataset Name:** Product Dataset

### Attributes

| Column       | Description                        |
| ------------ | ---------------------------------- |
| Product ID   | Unique identifier for each product |
| Product Name | Name of the product                |
| Brand Name   | Brand associated with the product  |
| Quantity     | Quantity of products               |
| Category     | Product category                   |
| Price        | Price of the product               |

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* Excel Formulas & Functions
* Data Exploration
* Conditional Analysis
* Text Manipulation

---

## 📋 Tasks Performed

### 1. Basic Data Exploration

Used Excel functions to calculate:

* **Total Price** of all products
* **Number of Products**
* **Average Product Price**

### 2. Minimum & Maximum Price

Identified:

* **Minimum Price**
* **Maximum Price**

using Excel `MIN()` and `MAX()` functions.

### 3. Logical Function – IF

Created a new column called **Price Range**.

Products were categorized based on their price:

| Condition    | Classification |
| ------------ | -------------- |
| Price ≥ $500 | High Price     |
| Price < $500 | Standard Price |

Used the Excel `IF()` function to perform this classification.

### 4. Conditional Functions – SUMIF & COUNTIF

Performed conditional analysis using:

* `SUMIF()` → Calculated the total price of products in the **Electronics** category.
* `COUNTIF()` → Counted the number of products with a price **less than $100**.

### 5. Text Functions – LEFT, RIGHT & MID

Created additional columns by extracting information from the **Product ID**.

| New Column   | Function  | Purpose                    |
| ------------ | --------- | -------------------------- |
| Day          | `LEFT()`  | Extract first 2 characters |
| Country Code | `RIGHT()` | Extract last 2 characters  |
| Month        | `MID()`   | Extract characters 4–6     |

---

## 📐 Excel Functions Used

```text
SUM()
COUNT()
AVERAGE()
MIN()
MAX()
IF()
SUMIF()
COUNTIF()
LEFT()
RIGHT()
MID()
```

---

## 📈 Key Learning Outcomes

Through this assignment, I practiced:

* Basic data exploration in Excel
* Using Excel formulas for data analysis
* Logical decision-making using `IF()`
* Conditional aggregation using `SUMIF()`
* Conditional counting using `COUNTIF()`
* Finding minimum and maximum values
* Text extraction using `LEFT()`, `RIGHT()`, and `MID()`
* Creating calculated columns
* Organizing and documenting an analysis project

---

## 📁 Project Files

This repository contains the following files:

```text
excel-data-exploration-analysis/
│
├── Raw_Dataset.xlsx
├── Excel_Data_Exploration.xlsx
└── README.md
```

**Raw_Dataset.xlsx**
Contains the original product dataset.

**Excel_Data_Exploration.xlsx**
Contains the completed Excel analysis, formulas, calculated values, and additional columns.

**README.md**
Contains the project description, objectives, tasks, tools, and learning outcomes.

---

## 🚀 About My Data Analytics Journey

I am a **Final-Year Biomedical Engineering student** currently developing my skills in **Data Analytics** with the goal of transitioning into the IT/Data Analytics field.

I am currently building my foundation in:

* 📊 Excel
* 🗄️ SQL
* 🐍 Python
* 📈 Power BI

This project is one of my initial portfolio projects demonstrating my practical learning in **Excel Data Analysis**.

---

## 👤 Author

**Hariharan A**

Aspiring Data Analyst | Final-Year Biomedical Engineering Student

---

## ⭐ Project Status

**Completed ✅**

This project represents my foundational practice in **Microsoft Excel for Data Analysis**.
