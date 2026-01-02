# Power BI – Employee Fluctuation Analysis (Demo Project)

My **LINKEDIN** [HERE](https://www.linkedin.com/in/matěj-frol%C3%ADk-183812230/).

## Overview
This repository contains a **demo Power BI project** focused on **employee fluctuation (turnover) analysis** in a simulated automotive manufacturing environment.

The project was created to demonstrate:
- HR data analysis skills
- Power BI data modeling
- DAX calculations
- Dashboard design and storytelling

> ⚠️ **Disclaimer**  
> All data used in this project are **synthetic (fictional)** and created solely for demonstration purposes.  
> The dashboard does **not represent any real company, employees, or HR records**.

---

## Project Goals
The main goal of this demo is to show how employee fluctuation can be analyzed from multiple perspectives:
- time (monthly, YTD),
- organizational structure,
- termination reasons,
- employee tenure,
- sickness and overtime,
- onboarding and training impact.

---

## Data Description (Synthetic)
The dataset simulates typical HR and attendance data:
- Employee master data
- Contract types (permanent / agency)
- Termination records and reasons
- Attendance, sickness, and overtime
- Organizational structure (division, department, section, team leader)

All relationships and values were intentionally designed to resemble realistic HR scenarios.

---

## Data Preparation
- Data transformation and cleaning in **Power Query**
- Relational data model created in **Power BI**
- Calculated columns and measures using **DAX**
- Time intelligence measures (monthly trends, YTD, before/after comparison)

---

## Report Pages Description

### 1. Fluctuation – Detail Overview
High-level overview of employee turnover.
- Monthly terminated employees
- Year-to-date (YTD) fluctuation trend
- Breakdown by division
- Permanent vs. agency employees
- Distribution by employee tenure

**Purpose:** Executive-style overview of fluctuation trends.

<img width="1158" height="642" alt="Snímek obrazovky 2026-01-02 153345" src="https://github.com/user-attachments/assets/78dd70c8-0090-4727-ba3a-8f785a3e8ee0" />

---

### 2. Overtime × Sickness × Fluctuation
Combined view of workload, health, and turnover.
- % sickness
- % overtime
- % fluctuation
- Monthly comparison within a selected year

**Purpose:** Demonstrate correlation analysis between multiple HR KPIs.

<img width="1162" height="650" alt="Snímek obrazovky 2026-01-02 153631" src="https://github.com/user-attachments/assets/6af8e18d-462d-44c0-bc1d-2b531417f6ba" />

---

### 3. Termination Reasons – Detail
Detailed view of (fictional) termination reasons.
- Text-based reasons
- Grouped categories:
  - Employer-initiated
  - Employee-initiated
  - Mutual agreement

**Purpose:** Show how qualitative HR data can be structured and visualized.

<img width="1163" height="652" alt="Snímek obrazovky 2026-01-02 153716" src="https://github.com/user-attachments/assets/97754f26-10a7-4831-bf47-bda4410014f4" />

---

### 4. Monthly Fluctuation
Monthly turnover across the organization.
- Terminated employees by month and division
- Total headcount
- Termination percentage
- Breakdown by section, team, and team leader

**Purpose:** Identify fluctuation patterns and organizational hotspots.

<img width="1162" height="652" alt="Snímek obrazovky 2026-01-02 153833" src="https://github.com/user-attachments/assets/821acc64-ab28-4a60-8edb-f12e258255f6" />

---

### 5. Year-to-Date (YTD) Fluctuation
Cumulative view of turnover.
- YTD terminated employees
- Cumulative trends by division
- Organizational breakdowns

**Purpose:** Management reporting and long-term trend analysis.

<img width="1160" height="653" alt="Snímek obrazovky 2026-01-02 154415" src="https://github.com/user-attachments/assets/806fe160-213e-4b61-87cc-4667ffc89418" />

---

### 6. Fluctuation Before and After Training (TWI)
Before/after comparison of turnover trends around training events.
- Termination % trend before training
- Termination % trend after training
- Trend lines and reference markers

**Purpose:** Demonstrate impact analysis and before/after logic.

<img width="1162" height="652" alt="Snímek obrazovky 2026-01-02 154854" src="https://github.com/user-attachments/assets/74f57f87-5044-4eb4-af69-de268585b192" />

---

### 7. Time in Company & Yearly Fluctuation
Employee tenure analysis.
- Distribution of employees by time in company
- Fluctuation rate by tenure group
- Detailed tenure buckets (weeks, months, years)

**Purpose:** Identify critical retention periods.

<img width="1162" height="647" alt="Snímek obrazovky 2026-01-02 155000" src="https://github.com/user-attachments/assets/93663fd2-8bdb-4c3a-93bf-4ba813fb8083" />

---

### 8. Sickness Overview
Combined view of tenure and sickness.
- Time in company vs. sickness %
- Detailed breakdown by tenure groups

**Purpose:** Show relationship between tenure and health indicators.

<img width="1161" height="648" alt="Snímek obrazovky 2026-01-02 155022" src="https://github.com/user-attachments/assets/3c041a9d-2364-47ac-a6be-1b7ea9fcd6b9" />

---

### 9. New Hire (Newbee) Analysis
Early attrition analysis.
- Monthly number of new hires
- Employees leaving before completing trial/training period
- Monthly comparison

**Purpose:** Demonstrate onboarding and early attrition analysis.

<img width="1157" height="646" alt="Snímek obrazovky 2026-01-02 155113" src="https://github.com/user-attachments/assets/5ef04d30-ded8-42f3-a454-abd1452e8f22" />

---

## Tools & Technologies
- Power BI
- Power Query
- DAX
- Excel (as data source)
- Synthetic data modeling

---

## Use Case
This project is intended as:
- A **portfolio showcase**
- A **demo of HR analytics capabilities**
- An example of **Power BI dashboard design and data storytelling**

---

## Author
**Matej Frolik**  
Medior Data/IT Analyst

