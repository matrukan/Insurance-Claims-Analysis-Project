# Insurance Claims KPI Dashboard

## 📌 Project Overview
This project simulates an **insurance claims analytics scenario** for Life & General Insurance, focusing on **KPI tracking**, **data quality**, and **visual reporting**.  
It demonstrates how SQL and Power BI can be used together to clean, transform, and visualize insurance data for better decision-making.  

---

## 🎯 Objectives
- Create a synthetic insurance claims dataset for analysis.
- Perform **data cleaning, transformation, and KPI calculations**.
- Build an **interactive Power BI dashboard** with filters and drill-down capabilities.
- Implement **basic data validation checks** to ensure reporting accuracy.

---

## 📂 Dataset Details
The dataset contains:
- **PolicyID** – Unique policy identifier.
- **CustomerID** – Unique customer identifier.
- **PolicyType** – Life / General.
- **ClaimID** – Unique claim number.
- **ClaimAmount** – Amount claimed by the policyholder.
- **ClaimStatus** – Approved / Rejected / Pending.
- **ClaimDate** – Date claim was filed.
- **SettlementDate** – Date claim was settled (if approved).
- **RiskCategory** – Low / Medium / High.
- **PolicyLapse** – Yes / No.

#### Insurance Claims Data Dictionary

| **Field**        | **Definition** |
|------------------|--------------------------------------------------------------------------------------------------------------------------------|
| PolicyID         | A unique identifier assigned to each insurance policy. |
| CustomerID       | A unique identifier assigned to each customer (policyholder). |
| PolicyType       | The category of insurance policy purchased (Life / General). |
| ClaimID          | A unique identifier assigned to each claim filed by a policyholder. |
| ClaimAmount      | The amount of money requested by the policyholder under a claim. |
| ClaimStatus      | The current processing stage of a claim (Approved / Rejected / Pending). |
| ClaimDate        | The date when the policyholder submitted the claim request. |
| SettlementDate   | The date when the insurer settled or closed the claim (if approved). |
| RiskCategory     | Classification of the policyholder or policy based on assessed risk (Low / Medium / High). |
| PolicyLapse      | Indicates whether a policy is active (No) or has lapsed (Yes). |


---

## ⚙️ Tools & Technologies
- **Python** → Synthetic data generation.
- **SQL** → Data cleaning, transformation, KPI calculations.
- **Power BI** → Interactive KPI dashboard creation.
- **Excel/CSV** → Data exchange between steps.

---

## 📊 KPIs Tracked
- **Claims Approval Rate**
- **Average Settlement Time**
- **Policy Lapse Rate**
- **Monthly Claim Trends**
- **Claims by Risk Category**

---

## 📈 Dashboard Features
- Filter by **Policy Type**, **Risk Category**, and **Date Range**.
- Drill-down into **monthly or weekly claims trends**.
- KPI cards for quick insights.
- Visual breakdown of **claims by status**.

---

## 📜 Steps to Reproduce
1. **Generate Data**  
   Run the `generate_insurance_data.ipynb` script to create `insurance_claims.csv`.

2. **Load Data into SQL**  
   Import the CSV into your SQL database (MySQL, SQL Server, or Azure SQL).

3. **Clean & Transform**  
   Use SQL scripts to:
   - Handle missing values.
   - Calculate KPIs.
   - Standardize date formats.

4. **Build Dashboard in Power BI**  
   - Connect Power BI to SQL or CSV.
   - Create KPI cards, trend lines, and category breakdowns.
