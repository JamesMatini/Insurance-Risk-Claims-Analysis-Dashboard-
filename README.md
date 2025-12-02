# Insurance Risk & Claims Analysis Dashboard

## Project Overview
This project is a **Power BI interactive dashboard** designed to help an insurance company analyze car insurance policies and claims. The goal is to provide a **centralized, data-driven view** of policyholder behavior, claim patterns, and risk factors, enabling informed business decisions.

Currently, policy and claims data are scattered across multiple sources, making it difficult for stakeholders to track performance and identify trends. This dashboard consolidates data into **key metrics and visualizations** to support risk assessment, customer segmentation, and policy optimization.

---
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/33e28fbe-2ef9-481b-a649-b6c8a6a01a88" />


## Business Requirements
The dashboard delivers insights through the following **KPIs**:

1. **Total Policies** – Size of the active customer base.  
2. **Total Claim Amount** – Overall financial impact of claims.  
3. **Claim Frequency** – How often claims are made.  
4. **Average Claim Amount** – Assess claim severity and risk exposure.  
5. **Gender-wise Total Policies** – Customer distribution across genders.

---

## Data Overview
The dataset contains detailed information about policyholders, their vehicles, and claims history. Key attributes include:

- **Demographics:** Birthdate, Gender, Marital Status, Education, Household Income, Parental Status.  
- **Vehicle Information:** Car Make, Model, Color, Year, Usage Type (Personal, Commercial, Commute), Coverage Zone.  
- **Claims Data:** Claim Amount, Claim Frequency, Kids Driving.

These fields enable segmentation, risk profiling, and identification of patterns across customer and vehicle attributes.

---

## Visualizations
The dashboard provides **dynamic, interactive visualizations** to explore policies and claims:

1. **By Car Use (Donut Chart)** – Policies and claims by usage type.  
2. **By Car Make (Bar Chart)** – Identify high-risk car brands.  
3. **By Coverage Zone (Donut Chart)** – Regional analysis of claims.  
4. **By Age Group (Histogram)** – Assess which age brackets file more claims.  
5. **By Car Year (Area Chart)** – Impact of car age on claims.  
6. **By Kids Driving (Ribbon Chart)** – Household risk analysis with young drivers.  
7. **By Education (Pie Chart)** – Correlation of education with insurance adoption.  
8. **By Education & Marital Status (Matrix Heat Grid)** – Combined effect on claims and policies.

All visuals are built around two dynamic measures: **Total Policies** and **Total Claim Amount**, enabling effective filtering, comparison, and segmentation.

---

## Business Value
- **Risk Assessment:** Identify high-risk customer segments and vehicle types.  
- **Claims Analysis:** Monitor claim frequency and severity.  
- **Customer Segmentation:** Tailor policies based on demographics, vehicle use, and household profile.  
- **Premium Optimization:** Design data-driven pricing strategies.  
- **Fraud Detection:** Spot unusual claim patterns based on demographics and vehicle attributes.  

---

## Tools & Technologies
- **Power BI Desktop** – Data visualization and dashboard creation.  
- **DAX (Data Analysis Expressions)** – For dynamic calculations and measures.  
- **Data Cleaning & Transformation** – Power Query and modeling.  

---

## How to Use
1. Load the dataset into Power BI.  
2. Use slicers and filters to explore specific demographics, car types, or geographic zones.  
3. Interact with charts to uncover insights about claims, risk, and policy distribution.  
4. Export dashboards for stakeholder presentations and reports.

---

## Dataset Fields Summary
| Field | Description | Business Use |
|-------|-------------|--------------|
| ID | Unique policyholder identifier | Track individual records |
| Birthdate | Date of birth | Age-based risk profiling |
| Car Color | Vehicle color | Explore patterns, fraud detection |
| Car Make/Model | Vehicle brand & model | Assess claim frequency & cost |
| Car Use | Personal/Commercial/Commute | Risk-based pricing |
| Car Year | Year of manufacture | Vehicle age vs claim risk |
| Coverage Zone | Geographic risk area | Regional risk analysis |
| Education | Highest education level | Segmentation & marketing |
| Gender | Male/Female/Other | Demographic analysis |
| Marital Status | Single/Married/Divorced | Risk profiling |
| Parent | Has children | Household driving behavior |
| Claim Amt | Total claim cost | KPI for financial impact |
| Claim Freq | Number of claims | KPI for risk frequency |
| Household Income | Annual income | Customer segmentation |
| Kids Driving | Number of licensed kids | Family risk assessment |

---

## Author
**James Matini**  
Email: [your email] | LinkedIn: [your LinkedIn profile]  

---

## License
This project is for **educational and professional portfolio purposes**. All data is anonymized for privacy.
