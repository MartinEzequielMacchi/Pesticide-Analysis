# 🧪 Pesticide Usage Analysis (US)

This project analyzes county-level pesticide usage for **423 compounds** across the contiguous United States. The dataset includes two estimation methods—**low** (assumes zero for unreported data) and **high** (imputes missing values from nearby districts). Comparing these methods helps reveal how assumptions impact agricultural risk assessments and public health interpretations.

## 🗂️ Dataset Columns
- **COMPOUND** – Pesticide name  
- **YEAR** – Measurement year  
- **STATE / COUNTY / CODES** – Location identifiers  
- **LOW_ESTIMATE / HIGH_ESTIMATE** – Pesticide usage in kilograms  

## 🎯 Objectives
- Identify states and counties with the highest pesticide usage  
- Compare low vs. high estimation methods  
- Analyze distribution of pesticide usage by state  
- Explore yearly trends for selected compounds  

## 🛠️ Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- missingno  
- scipy  
