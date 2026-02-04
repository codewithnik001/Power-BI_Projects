# 🛡️ Insurance Claims & Risk Analysis Dashboard

### **Project Overview**
This Business Intelligence (BI) project analyzes insurance policy and claims data to assess **Risk Exposure** and **Profitability**. By visualizing key metrics such as **Loss Ratios**, **Claim Frequency**, and **Premium Revenue**, this dashboard helps stakeholders identify high-risk demographic segments and optimize pricing strategies.

The analysis focuses on understanding the relationship between policyholder attributes (Age, Region, Income) and their likelihood of filing claims.

---

### **📊 Live Dashboard**
**[View the Interactive Dashboard Here] (Paste your NovyPro / Power BI Service Link Here)**

---

### **📸 Dashboard Screenshots**
*(Add your dashboard images below. Replace `image_path` with your actual file names)*


*Figure 1: Executive Summary & Loss Ratio Analysis*
<img width="1318" height="741" alt="Screenshot 2026-02-04 115631" src="https://github.com/user-attachments/assets/4f2de72e-db55-48d1-b472-4fd1d87e0f1f" />



*Figure 2: Policyholder Risk Profile & status*
<img width="1302" height="722" alt="Screenshot 2026-02-04 115711" src="https://github.com/user-attachments/assets/cee9cf46-724f-4631-95fa-a66605f37e19" />


---

### **🎯 Key Business Problems Solved**
1.  **Risk Assessment:** Which customer segments (Age, Gender, Region) have the highest **Loss Ratio** (Claims Paid vs. Premiums Collected)?
2.  **Revenue Performance:** How is the total premium growth trending Month-over-Month (MoM)?
3.  **Claims Analysis:** What is the frequency of claims across different policy types?
4.  **Customer Profiling:** Which demographics are the most profitable (Low Risk, High Premium)?

---

### **🛠️ Tools & Techniques Used**
* **Power BI Desktop:** The core tool for visualization and report building.
* **Power Query (ETL):**
    * Processed raw policy and claims datasets.
    * Handled missing values and grouped age brackets for demographic analysis.
* **Data Modeling:**
    * Built a **Star Schema** linking the Fact Table (Claims/Transactions) to Dimension Tables (Customers, Policies, Calendar).
    * Created standard "One-to-Many" relationships for accurate filtering.
* **DAX
