# 🧾 Online Retail Dataset (2010–2011)

This repository contains the **Online Retail Dataset** used in the **Tata Data Visualization: Empowering Business with Effective Insights** virtual experience program on [Forage](https://www.theforage.com/).  

The dataset records transactions from a **UK-based online store** between **December 2010 and December 2011**.  
It is commonly used for learning and practicing data cleaning, analysis, and visualization with tools like **Power BI**, **Excel**, and **Python**.

---

## 📊 Dataset Description

Each row represents a product transaction made by a customer.  
The dataset provides essential fields for analyzing sales, customer behavior, and regional performance.

| Column Name | Description |
|--------------|-------------|
| **InvoiceNo** | Unique identifier for each invoice. Duplicate values indicate multiple items in a single transaction. |
| **StockCode** | Product (item) code for each sold item. |
| **Description** | Product name or description. |
| **Quantity** | Number of units sold per item. Negative values indicate returns. |
| **InvoiceDate** | Date and time when the transaction occurred. |
| **UnitPrice** | Price per unit (in pounds sterling). |
| **CustomerID** | Unique numeric identifier for each customer. |
| **Country** | Country where the customer resides or where the order was billed/shipped. |

---

## 🧹 Data Notes

- Contains **over 500,000 transaction records**.  
- Includes some **negative values** in `Quantity` and `UnitPrice` (representing returns or errors).  
- Includes **missing values** in `CustomerID` which may require cleaning.  
- **Currency:** GBP (£)  
- **Time Period:** December 2010 – December 2011  
- **Primary Market:** United Kingdom (with international transactions included)

---

## 📂 File Information

- **File Name:** `OnlineRetail.csv`  
- **Format:** CSV (Comma-Separated Values)  
- **Encoding:** UTF-8  
- **Size:** Approximately 24 MB  

---

## ⚙️ Usage

This dataset can be used for:

- Practicing **data cleaning and transformation**  
- Conducting **exploratory data analysis (EDA)**  
- Creating **Power BI or Tableau dashboards**  
- Performing **customer segmentation** and **revenue pattern analysis**  
- Demonstrating **data storytelling and visualization skills**

---

## 📘 Source and Attribution

This dataset was obtained from the  
**[Tata Data Visualization: Empowering Business with Effective Insights](https://www.theforage.com/)**  
virtual experience program on **Forage**, where it is provided for educational purposes.

The **original dataset** was published by:  
> **Dr. Daqing Chen**, Department of Computer Science and Information Systems, Middlesex University, London.  
> Hosted by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail), 2015.

**Citation:**  
> Chen, Daqing. *“Online Retail Data Set.”* UCI Machine Learning Repository, 2015.

---

## 🪪 License

This dataset is provided **for educational and research purposes only**.  
All rights and credit remain with the **original author (Dr. Daqing Chen)** and the **UCI Machine Learning Repository**.  
The Tata Forage program uses it under educational license.

---

