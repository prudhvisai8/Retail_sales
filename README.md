# Retail Transaction Dataset

A small, synthetic dataset of retail transactions for demonstration, analysis, and educational purposes. Ideal for practicing data analysis, visualization, SQL queries, or building dashboards in tools with Excel, Power BI,

---

## 📊 Dataset Overview

This dataset contains **16 retail transactions** with customer and purchase details.

### File
- `retail_transactions.csv` *(included in this repository)*

---

## 📑 Columns

| Column            | Description                                      | Example       |
|-------------------|--------------------------------------------------|---------------|
| `Transaction ID`  | Unique identifier for each transaction           | 1             |
| `Date`            | Date of transaction *(masked as `########`)*     | ########      |
| `Customer ID`     | Unique customer identifier                       | CUST001       |
| `Gender`          | Customer gender (`Male` / `Female`)              | Male          |
| `Age`             | Customer age (in years)                          | 34            |
| `Product Category`| Category of product purchased                    | Beauty        |
| `Quantity`        | Number of units purchased                        | 3             |
| `Price per Unit`  | Price of one unit (in currency units)            | 50            |
| `Total Amount`    | Total transaction value (`Quantity × Price`)     | 150           |

---

## 📈 Sample Data

```csv
Transaction ID,Date,Customer ID,Gender,Age,Product Category,Quantity,Price per Unit,Total Amount
1,########,CUST001,Male,34,Beauty,3,50,150
2,########,CUST002,Female,26,Clothing,2,500,1000
3,########,CUST003,Male,50,Electronics,1,30,30
...
