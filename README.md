# online store Sales Analysis Project: From Data Cleaning to Dynamic Dashboards  

## Overview  
This project involves a comprehensive sales analysis, employing **Power Query** for data cleaning, **Power Pivot** for data modeling, and dynamic dashboard creation. The goal is to extract valuable insights and enable informed decision-making.  

## Project Workflow  

### Data Cleaning Process  

Data cleaning was performed on the following sheets:  
- **Orders**  
- **People**  
- **Returns**  
- **Shipping Cost**  

Using **Power Query**, the following transformations were applied:  
- Removed unnecessary columns and rows.  
- Reformatted column headers for clarity.  
- Split and merged fields for consistency.  

Additional cleaning steps included:  
1. **Missing Data Handling**  
   - Numerical Columns: Imputed missing values using the mean or median.  
   - Categorical Columns: Imputed using the mode to avoid bias.  

2. **Outlier Detection and Treatment**  
   - Identified outliers using z-scores and IQR techniques.  
   - Treated outliers by capping or transforming them.  

3. **Data Type Corrections**  
   - Ensured correct data types (numeric, categorical, datetime).  

4. **Date Formatting**  
   - Standardized date columns to a consistent format.  

5. **Duplicated Records**  
   - Removed duplicates after verification.  

6. **Normalization and Standardization**  
   - Applied normalization and standardization techniques for compatibility.  

7. **Consistency Checks**  
   - Checked and corrected typos and case inconsistencies in categorical variables.  

8. **Encoding**  
   - Encoded categorical variables as needed.  

9. **Null Value Strategy Documentation**  
   - Documented all null value treatment decisions.  

### Data Modeling with Power Pivot  

The cleaned data was modeled using **Power Pivot**:  
- Established relationships between the **Orders**, **People**, **Returns**, and **Shipping Cost** tables.  
- Defined primary and foreign keys for seamless data integration.  

Key measures developed:  
- `Total Profit`: Overall profitability.  
- `Total Customers (CX)`: Total number of customers.  
- `Total Orders`: Total number of sales orders.  
- `Profit per Customer`: Profitability per customer.  
- `Profit per Order`: Average profit per order.  
- `Average Profit per Order`: Profit trends over time.  

### Key Performance Indicators (KPIs)  
- Developed KPIs to visualize profit goals and track performance effectively.  

### Sales Questions for Analysis  
- Focused analysis on:  
  - Sales performance.  
  - Customer trends.  
  - Order frequency.  
  - Overall profitability.  

### Dynamic Dashboard Creation  

Built an interactive and dynamic dashboard using **Power BI** (or **Excel Power Pivot**) with:  
- Slicers for filtering data by key variables.  
- Visualizations for:  
  - `Profit per Customer` and `Profit per Order`.  
  - `Total Profit` and `Average Profit per Order`.  
  - KPI-based profit assessments.  

### Visualizations and Reporting  

Created visual elements to display:  
- Sales performance metrics.  
- Profitability trends.  
- KPIs for quick insights.  

## Conclusion  

This project enabled improved sales performance monitoring and decision-making through:  
- **Cleaned and Modeled Data:** Ensuring high-quality, reliable datasets.  
- **Dynamic Dashboard:** Offering an interactive platform for exploring insights.  
- **Effective KPIs:** Highlighting critical performance measures.  

---

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/your-profile) for questions or collaboration opportunities! 
