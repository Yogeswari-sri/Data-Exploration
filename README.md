# Data-Exploration
Summarize the Datasets shape,data types and Statistics. 
-----------------------------------
Data Cleaning should be done
✔ Handling Missing values using IF and AverageIF Function to Replace it.
---------------------------------
# Data Exploration in Excel – SalesDatabase

This repository contains an exploratory analysis of the **SalesDatabase** dataset using Excel functions and techniques.  
The goal is to demonstrate how raw data can be cleaned, transformed, and explored to uncover insights before advanced modeling or visualization.
----------------------------

## Contents
- `Data_Exploration_Report.md` – Detailed report of findings
- `SalesDatabase.xlsx` – Original dataset
- Visualizations (charts, pivot tables) – To be added
- Example formulas and transformations

## Key Exploratory Steps
1. **Data Cleaning**
   - Removed duplicates
   - Standardized date and currency formats
   - Handled missing values with averages or placeholders

2. **Basic Calculations**
   - Total Price, Count, Average
   - Min & Max Price

3. **Categorization**
   - Created a Price Range column using `IF` function  
     Example: `=IF(B2>=500,"High Price","Standard Price")`

4. **Category-Specific Analysis**
   - `SUMIF` for Electronics category totals  
   - `COUNTIF` for products under $100

5. **Text Functions**
   - Extracted Day, Country Code, and Month using `LEFT`, `RIGHT`, `MID`

6. **Visual Exploration**
   - Bar charts for category totals
   - Pie charts for price ranges
   - Pivot tables for dynamic exploration

## Insights
- Electronics dominate overall sales
- Fashion & Kitchen categories show lower averages
- High Price products are limited but impactful

## Next Steps
- Add charts and dashboards for better visualization
- Expand analysis with pivot tables and slicers

- OUTPUT:

<img width="1600" height="900" alt="e" src="https://github.com/user-attachments/assets/2a53a2e1-3cde-428e-975d-bb4f647f8c69" />

- Automate reporting with Power Query or Python scripts

