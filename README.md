# Employee Attrition Analysis

An exploratory data analysis on the [IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data) from Kaggle, showcasing my data analytics skills.

## **Project Phases**
This project follows the six key phases of data analysis:
1. **Ask**
2. **Prepare**
3. **Process**
4. **Analyze**
5. **Share**
6. **Act**

---

## **1. ASK**
In this phase, I define the scope of the project by formulating key questions:

**Q1.** Which age group left the company the most? 
**Q2.** What are the attrition trends based on department? 
**Q3.** How does salary impact employee attrition? 
**Q4.** What patterns emerge from educational backgrounds in relation to attrition? 
**Q5.** What percentage of employees who left were working overtime?

Answering these questions will help streamline the data analysis process.

---

## **2. PREPARE**
The dataset is sourced from Kaggle, an open-source platform for datasets. While this is not an official dataset from a company, it simulates real HR analytics data.

- The dataset contains **1,470 employee records**.
- Since this is second-hand data, assumptions and validation checks are necessary before analysis.

---

## **3. PROCESS**
In this phase, I check the integrity of the data and clean it using various techniques.

### **Data Cleaning Steps:**
- **Data Types:** Verified all column data types and corrected inconsistencies using Power Query.
- **Range Checks:** Ensured numerical values fell within expected ranges.
- **Handling Null Values:** Verified completeness of mandatory fields.
- **Duplicate Removal:** Checked and eliminated any duplicate records.
- **Standardization:** Ensured consistent formatting (e.g., trimming spaces, correcting labels).
- **Error Correction:** Found an inconsistency in the `EmployeeCount` column where one value contained an 'h'. Replaced it with `1`, as each row represents a single employee.

---

## **4. ANALYZE**
After cleaning the data, I performed an in-depth analysis using **Excel** and **Power BI**.

### **Key Findings:**
- **Salary & Attrition:** Employees with lower salaries had significantly higher attrition rates.
  - Created income segments: **Low, Medium, and High**.
  - Used a **DAX measure** (`AttritionRate`) to show how attrition varied across salary levels.
  - Found that **low-income employees had the highest attrition rate**.

- **Overtime & Attrition:**
  - Created a **DAX measure** to count employees who left.
  - Used a **pie chart** to visualize the proportion of attrition among employees working overtime.
  - Found that **more than 50% of employees who left were working overtime**.

- **Department-wise Trends:**
  - Built a **line chart** to track attrition trends across departments.
  - **Sales and HR had the highest attrition rates**.
  - Sales attrition was **significantly higher** than other departments.

- **Age & Attrition:**
  - Created an **Age Grouping column** in Power Query.
  - Used a **bar chart** to compare attrition across age groups.
  - Found that **18-22-year-olds had the highest attrition rate**, particularly in the **Sales department**.

- **Education Field & Attrition:**
  - Created a **stacked column chart** showing attrition per education field.
  - **Life Sciences and Medical backgrounds** had the highest number of employees leaving.
  - This was expected since **most employees belonged to these fields**.

---

## **5. SHARE**
This phase involves presenting the analysis effectively through **data visualizations** in Power BI.

### **Dashboard Design:**
- Used **color-coded visuals** to improve clarity.
- **Simplified charts** by removing unnecessary labels.
- **Highlighted key insights** for better storytelling.
- **Interactive filters (slicers)** were added to explore data based on:
  - **Employee Status (Working / Non-Working)**
  - **Gender (Male / Female)**
- **DAX Measures** were used to dynamically display key metrics.

---

## **6. ACT**
Based on the findings, I propose the following recommendations:

1. **Increase salaries for low-income employees** to reduce attrition.
2. **Improve training & onboarding for 18-22-year-olds** to help retain younger employees.
3. **Reduce excessive overtime** to prevent burnout and high turnover.
4. **Provide additional support for Sales employees**, as their attrition rate is disproportionately high.
5. **Conduct further research on HR attrition trends** to understand underlying causes.

---

### **Conclusion**
This analysis helped identify key factors affecting attrition and provided data-driven recommendations to improve employee retention. Through **Power BI visualizations**, stakeholders can easily interpret the insights and take informed actions.

---

### **Future Improvements**
- Perform a **Chi-Square Test** in Power BI to statistically determine the significance of attrition factors.
- Implement **Machine Learning** models to predict future attrition trends.
- Expand analysis using **external industry benchmarks** to compare with real-world data.

---

### **Tools Used:**
✅ Microsoft Excel (Initial data exploration)  
✅ Power Query (Data Cleaning & Transformation)  
✅ DAX (Custom Measures & Calculations)  
✅ Power BI (Data Visualization & Dashboard)  

---

This documentation is designed for **GitHub**, making it clear and structured for readers. Let me know if you need any modifications! 🚀

