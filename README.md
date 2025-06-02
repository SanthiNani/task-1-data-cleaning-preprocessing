# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset
**Mall_Customers_RAW.csv** – Customer information including gender, age, income, and spending behavior.

## 🧼 Objective
Clean and preprocess the dataset for downstream analytics and modeling tasks.

## 🛠 Tools Used
- Python 3
- Pandas

## ✅ Cleaning Summary

| Step | Action |
|------|--------|
| 1 | Removed duplicate rows |
| 2 | Standardized text in `Gender` column |
| 3 | Renamed columns to lowercase with underscores |
| 4 | Filled missing values in `Age`, `Annual Income`, and `Spending Score` using median |
| 5 | Converted `CustomerID` to string |

## 🗂 Output
- `cleaned_mall_customers.csv` – Final cleaned dataset
  ![Screenshot 2025-06-02 194952](https://github.com/user-attachments/assets/a1cb55c3-dab8-4b3e-81b3-956be2a46ce0)

- `data_cleaning_script.ipynb` – Jupyter notebook with code

## 📁 Folder Structure
```

task-1-data-cleaning/
├── Mall_Customers_RAW..csv
├── cleaned_mall_customers.csv
├── data_cleaning_script.ipynb
└── README.md

```
