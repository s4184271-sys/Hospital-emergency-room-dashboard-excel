# Hospital Emergency Room Dashboard — Excel

An Excel-based hospital operations dashboard analyzing approximately **9,200 emergency-room admission records** to understand patient volume, waiting time, satisfaction, and department-level performance.

## Business Questions

- How many patients are being admitted?
- What is the average ER waiting time?
- What is the average patient satisfaction score?
- How does patient volume change over time?
- Which department referrals receive higher patient volumes?
- Where may operational bottlenecks be occurring?
- How do waiting time and satisfaction vary across filters such as department and gender?

## Solution

The project follows an end-to-end Excel BI workflow.

### 1. Data Transformation — Power Query

- Corrected inconsistent data types
- Cleaned null and formatting issues
- Merged and split columns where required
- Standardized patient identifiers and timestamps

### 2. Data Modeling — Power Pivot

- Loaded the cleaned data into the Data Model
- Structured calculated columns for reporting
- Prepared the model for dashboard analysis

### 3. Analysis — DAX

Used conditional logic such as `IF` and `IFS` to flag long waiting times and segment satisfaction scores into performance bands.

### 4. Dashboard

The dashboard contains:
- KPI cards for ER volume, average wait time, and average satisfaction
- Admission trend charts
- Department-level comparisons
- Interactive slicers for department, gender, and date

## Dataset

Approximately **9,200 patient-level ER admission records** with fields including Patient ID, Admission Date, Name, Gender, Age, Race, Department Referral, Admission Flag, Satisfaction Score, and Wait Time.

## Goal

The dashboard is designed as a hospital operations reporting tool, helping users identify trends and areas that may require further investigation without manually reviewing raw records.

## Current Scope

The project focuses on Power Query, Power Pivot, DAX fundamentals, and interactive reporting.

Planned extensions include:
- DAX time-intelligence measures such as YTD and period-over-period comparisons
- Additional dimension tables and relationships

## Tools

**Microsoft Excel · Power Query · Power Pivot · DAX**

## Acknowledgement

Power Query, Power Pivot, and DAX concepts were learned through Satish Dhawale's tutorials.
