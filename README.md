"# Data_Analytics_Project" 
# Data_Analytics_Project
# FMCG Data Analytics Project 📊

This repository contains an end-to-end data analytics project focused on the **Fast-Moving Consumer Goods (FMCG)** sector. The goal is to explore, analyze, and derive business insights by merging sales and warehouse data.

## Project Structure

- `data_analytics.ipynb` – Initial EDA on Sales and Warehouse datasets
- `complete_analysis.ipynb` – Full project pipeline: merging datasets, EDA, visualization, and insights
- `README.md` – Project overview and documentation


##  Datasets Used

1. **Sales Dataset**  
   Contains 1000 records with features like:
   - `Date`, `Product_Category`, `Sales_Volume`, `Price`, `Promotion`, `Store_Location`, etc.

2. **Warehouse Dataset**  
   Contains 25,000 records with features such as:
   - `WH_capacity_size`, `zone`, `num_refill_req_l3m`, `flood_proof`, `govt_check_l3m`, etc.

---

##  Data Cleaning

- Checked for null/missing values
- Verified column data types
- Ensured proper merging using `Store_Location` and `Location_type`


##  Exploratory Data Analysis (EDA)

- Distribution plots for `Sales_Volume`, `Price`, and `Promotion`
- Boxplots to compare sales volume across promotions
- Correlation matrix heatmaps
- Merged insights based on zone, regional warehouse, and product categories


##  Key Insights

- Promotional offers positively affect sales volume
- Regional warehouse zones with more government-approved certifications show efficient stock levels
- Warehouses with past transport issues show higher stock accumulation


##  Future Enhancements

- Implement predictive modeling (e.g., XGBoost or Random Forest) for demand forecasting
- Add interactive dashboards using Plotly or Streamlit
- Include time-series trend analysis for seasonal products


