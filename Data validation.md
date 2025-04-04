## **Data Validation**

To ensure data integrity before generating reports, a validation check was conducted in **Power BI** after importing data. The task was assigned by **Tony Sharma** via **Microsoft Teams Taskbot**, along with a **Word document** containing benchmark figures.

---

### **Validation Workflow**

1. **Power BI Setup:**
   - Launched **Power BI Desktop**.
   - Added the **Fiscal_Year** field from the **Dim_Date** table to the rows of a table visual.
   - Pulled relevant data from **Fact tables** for validation.
   - Created a table visualization to compare actual values with benchmark targets.

2. **Benchmark Targets:**

   - **Total Sales Quantity (in Millions):**
     - 2018 → 3.45415M
     - 2019 → 10.78465M
     - 2020 → 20.7734M
     - 2021 → 50.16472M

   - **Total Forecast Quantity (in Millions):**
     - 2022 → 86.82346M

   - **FY 2022 Metrics:**
     - Products Sold → 345
     - Active Customers → 209
     - Active Markets → 27

---

### **Issue Found & Resolution**

- A **discrepancy** was identified in the **Total Forecast Quantity for 2022**.
- The issue was escalated to the **Data Engineer**, who confirmed that the product dataset was recently updated.
- Further investigation with **Product Owner Nick Puri** revealed that a **new product (AQ Marquee P4)** had been launched.
- The missing forecast quantity of **376K** was attributed to this new product.
- After the **database was updated**, a refresh and revalidation in Power BI showed that all figures matched the benchmark values.

---

✅ **Conclusion:**  
With the updated dataset now fully aligned with the benchmark figures, the data was validated and is ready for accurate reporting.

