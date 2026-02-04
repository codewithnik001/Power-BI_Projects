# 📊 Sales Data Analysis & Forecasting Dashboard

### **Project Overview**
This project involves a comprehensive analysis of sales performance using **Power BI**. The goal was to transform raw sales records into an interactive dashboard that tracks Key Performance Indicators (KPIs) such as **Total Revenue, Profit Margins, and Sales Growth**.

By visualizing data across multiple dimensions (Region, Product, and Time), this dashboard empowers stakeholders to identify high-performing segments and uncover opportunities to optimize inventory and pricing strategies.

---

### **📊 Live Dashboard**

<a href ="https://github.com/codewithnik001/Power-BI_Projects/blob/main/Retail%20Sales%20Performance%20Analysis/Sales%20Data%20Analysis.pbix">Dashboard download link!</a>

---

### **📸 Dashboard Screenshots**


![Sales Overview](<img width="1159" height="668" alt="Screenshot 2026-01-11 155535" src="https://github.com/user-attachments/assets/baf1bfe3-f3de-4e99-834d-627eeb2b9f0d" />
)
*Figure 1: Executive Sales Summary & KPI Cards*



---

### **🎯 Key Business Problems Solved**
1.  **Revenue & Profit Tracking:** How are sales trending Month-over-Month (MoM) and Year-over-Year (YoY)?
2.  **Regional Performance:** Which regions are contributing the most to the bottom line, and which are underperforming?
3.  **Product Strategy:** Which products are the "Cash Cows" (High Sales, High Profit) vs. "Loss Makers"?
4.  **Forecasting:** What is the projected sales trend for the next quarter based on historical patterns?

---

### **🛠️ Tools & Techniques Used**
* **Power BI Desktop:** Used for data ingestion, modeling, and visualization.
* **Power Query (ETL):**
    * Cleaned and transformed raw data (removed duplicates, handled null values, fixed data types).
    * Created conditional columns for custom categorization.
* **Data Modeling:**
    * Designed a **Star Schema** with Fact tables (Sales) and Dimension tables (Products, Customers, Dates).
    * Established active relationships (One-to-Many) to ensure accurate filtering.
* **DAX (Data Analysis Expressions):**
    * Created explicit measures for `Total Sales`, `Total Profit`, `Profit Margin %`.
    * Used Time Intelligence functions like `SAMEPERIODLASTYEAR` and `DATESYTD` for growth analysis.

---

### **💡 Key Insights**
* **Top Performer:** The **[Insert Top Region, e.g., West]** region accounts for **XX%** of total revenue.
* **Profit Drivers:** While **[Product A]** has the highest sales volume, **[Product B]** delivers the highest profit margin.
* **Seasonality:** Sales consistently peak in **[Insert Month, e.g., Q4/December]**, suggesting a need for inventory stocking in Q3.

---

### **🚀 How to Use This Repository**
1.  **Download:** Clone the repository or download the `.pbix` file.
2.  **Open:** Open the file in **Power BI Desktop**.
3.  **Interact:** Use the slicers on the left panel to filter by Year, Region, or Product Category to explore the data dynamically.

---

* **Author:** Nikhil Goswami
* *Connect with me on LinkedIn!* : [Click Here](https://www.linkedin.com/in/nikhil-goswami-5938431aa/)
