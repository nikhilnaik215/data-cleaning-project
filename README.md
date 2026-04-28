# 🧼 Student Data Cleaning Project

<p align="center">
  <b>Cleaning messy data using Pandas 🚀</b>
</p>

---

## 📌 Project Overview
This project demonstrates how raw student data can be cleaned and prepared using **Python (Pandas)**.  
The dataset contained missing values, inconsistent formats, and duplicate records which were handled step by step.

---

## 🧹 Data Cleaning Steps

✔ **Duplicate Removal**  
Removed repeated rows to maintain data integrity  

✔ **Handling Missing Values**  
- Filled numeric columns using mean  
- Filled categorical columns using mode  

✔ **Text Cleaning**  
- Removed unwanted spaces and symbols  
- Standardized text values  

✔ **Data Standardization**  
- Converted inconsistent values (Y/N → Yes/No)  
- Cleaned phone numbers to numeric format  

✔ **Filtering Data**  
- Removed rows with critical missing values  

---

## 📊 Workflow

```mermaid
graph LR
A[Raw Data] --> B[Check Missing Values]
B --> C[Clean Data]
C --> D[Remove Duplicates]
D --> E[Save Clean Data]
