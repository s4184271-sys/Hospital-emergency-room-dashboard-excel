# Hospital Emergency Room Dashboard (Excel | Power Query · Power Pivot · DAX)

An Excel-based BI dashboard analyzing ~9,200 ER patient admission records to surface trends in patient volume, wait times, and satisfaction scores — built to simulate a real hospital operations reporting tool.

##  Overview

This project takes raw, messy ER admission data and turns it into an interactive, decision-ready dashboard using Excel's Power Query, Power Pivot, and DAX toolchain — no external BI tool required.

##  Dataset

- ~9,200 rows of patient-level ER admission records
- Fields: Patient ID, Admission Date, Name, Gender, Age, Race, Department Referral, Admission Flag, Satisfaction Score, Wait Time

##  What's Inside

**Data Transformation (Power Query)**
- Corrected inconsistent data types across date and numeric fields
- Merged and split columns to standardize patient identifiers and timestamps
- Cleaned nulls and formatting issues prior to modeling

**Data Modeling (Power Pivot)**
- Loaded the cleaned dataset into Power Pivot
- Structured calculated columns to support department- and time-based reporting

**DAX Measures**
- Conditional logic (`IF` / `IFS`) to flag long wait times and segment satisfaction scores into performance bands

**Dashboard**
- KPI cards: daily ER volume, average wait time, average satisfaction score
- Bar and line charts for admission trends and department-level performance
- Slicers for interactive filtering by department, gender, and date

##  Goal

Give a hospital ops manager a quick, at-a-glance view of where bottlenecks are forming — e.g., departments with longer wait times or lower satisfaction — without needing to dig through raw data.

##  Next Steps

- Add DAX time intelligence measures (YTD, period-over-period comparisons)
- Expand data model with relationships across additional dimension tables

##  Acknowledgements

Learned Power Query, Power Pivot, and DAX fundamentals from Satish Dhawale's YouTube tutorials.

## Feedback

Open to feedback from anyone working in BI/analytics — particularly on the data model structure and DAX measures. Feel free to open an issue or reach out.
