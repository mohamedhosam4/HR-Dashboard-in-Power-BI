
# HR Dashboard in Power BI

**An interactive Power BI dashboard visualizing key HR metrics for strategic workforce insights and decision-making.**

**Repository:** [mohamedhosam4/HR-Dashboard-in-Power-BI](https://github.com/mohamedhosam4/HR-Dashboard-in-Power-BI)

---

## 📊 Overview

This Power BI dashboard presents a comprehensive view of the organization's HR data, analyzing a workforce of **2,845 employees**. It delivers detailed insights into:

- Hiring trends  
- Employee demographics  
- Gender and marital distribution  
- Job and departmental structures  
- Training costs and duration  
- Performance metrics

---

## 📸 Dashboard Preview

### Main Dashboard

![HR Dashboard Main](https://github.com/mohamedhosam4/HR-Dashboard-in-Power-BI/blob/main/Screenshot%202025-05-31%20001435.png)

### Filters Page

![HR Dashboard Filters](https://github.com/mohamedhosam4/HR-Dashboard-in-Power-BI/blob/main/Screenshot%202025-05-31%20001444.png)

---

## 📁 Data Profile

- **Source File:** `Cleaned_HR_Data_Analysis.csv`
- **Total Records:** 2,845
- **Fields:** 28

| Column                  | Description                            |
|-------------------------|----------------------------------------|
| Employee ID             | Unique identifier                      |
| Start Date              | Date of hire                           |
| Job Title               | Role or position title                 |
| Business Unit           | Organizational unit                    |
| Status                  | Current (Active) or former (Terminated)|
| Employment Type         | Full-time, part-time, contractor, etc. |
| Department              | Department name                        |
| Division                | Business division                      |
| Date of Birth           | Employee birth date                    |
| State                   | Geographic location                    |
| Gender                  | Male / Female                          |
| Marital Status          | Single, Married, Divorced, Widowed     |
| Performance Score       | Annual performance rating              |
| Engagement Score        | Survey-based engagement score          |
| Satisfaction Score      | Job satisfaction score                 |
| Work-Life Balance Score | Balance score based on survey          |
| Training Date           | Date of training session               |
| Training Program        | Course or training name                |
| Training Type           | Online, In-person, etc.                |
| Training Outcome        | Completed or Failed                    |
| Training Duration       | Duration in days                       |
| Training Cost           | Cost in USD                            |
| Age                     | Employee age                           |

---

## 🧩 Dashboard Components

### 1. **KPI Summary Tiles**

- 👥 **Total Employees:** 2,845  
- 👨 **Male Percentage:** 44%  
- 📈 **Average Performance Score:** 2.97  
- 📅 **Total Training Days:** 8,461  
- 💰 **Total Training Cost:** $1.59M  

---

### 2. **Hiring Trends**

- **New Hires per Year:** Line chart shows increase from 248 in 2018 to a peak of 594 in 2022, then decline to 319 in 2023.
- **Employee Status by Hire Year:** Visual split of active vs. terminated staff over the years.

---

### 3. **Demographic Distribution**

- **Marital Status:** Balanced distribution across Single (24.04%), Married (25.69%), Divorced (24.6%), and Widowed (25.66%).
- **Gender Distribution:** 55.82% Female and 44.18% Male.
- **Gender by Division:** Breakdown of male and female representation across various divisions.

---

### 4. **Organizational Structure**

- **By Department:**
  - Production (1,910 employees)
  - IT/IS (409)
  - Sales (311)
  - Software Engineering (112)
  - Admin Offices (79)
  - Executive Office (24)

- **By Job Title:** Most common titles include:
  - Production Technician (1,241)
  - Area Sales Manager (486)
  - Production Manager (277)

---

### 5. **Training Overview**

- **Training Metrics:**
  - Days: 8,461
  - Cost: $1.59 million
- **Metrics visualized:** Total training days and associated costs, highlighting learning investment.

---

### 6. **Filters & Interactivity**

The dashboard includes a dedicated filters page with slicers for dynamic data exploration:

- 🔄 **Employee Status:** Active / Terminated  
- 🏢 **Department Type:** Select from 6 departments  
- ⚧️ **Gender:** Male / Female  

These filters allow users to drill down and focus on specific employee segments.

---

## 📂 Files Included

- `HR_Dashboard.pbix` – The Power BI dashboard file  
- `Cleaned_HR_Data_Analysis.csv` – The cleaned dataset used for visualization  
- `README.md` – Documentation for this project  

---

## 🧠 Insights & Use Cases

- Strategic workforce planning  
- Diversity and inclusion tracking  
- Departmental performance analysis  
- Training ROI monitoring  
- Demographic segmentation

---

## ✅ How to Use

1. Clone this repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Connect to the provided dataset or replace it with your own  
4. Use the interactive filters and visuals for analysis  
