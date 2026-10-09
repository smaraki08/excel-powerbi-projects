# Data Analytics Projects: Excel & Power BI

Two hands-on data analytics projects built as part of my data analyst portfolio:

1. **Call Center Report 2023** – an interactive Excel dashboard
2. **Sales Analysis Dashboard** – a Power BI report

---

## Repository Structure

```
├── excel-project/
│   └── excel-project-1.xlsx
├── powerbi-project/
│   └── powerbi-project-1.pbix
├── screenshots/
│   ├── excel-dashboard.png
│   └── powerbi-dashboard.png
└── README.md
```

---

## 1. Call Center Report 2023 (Excel)

**File:** `excel-project/excel-project-1.xlsx`

### Overview
An Excel dashboard that analyses 1,000 customer support calls from 2023 to understand call volume, spending, call duration and customer satisfaction across representatives and cities.

### Dataset
The `Data` sheet has 1,000 rows with these columns:

| Column | Description |
|---|---|
| Call number | Unique ID of the call |
| Customer ID | Customer who made the call |
| Duration | Length of the call |
| Representative | Support representative (R01 to R05) |
| Date of Call | Date the call took place |
| Purchase Amount | Amount purchased during the call |
| Satisfaction Rating | Customer rating of the call |
| FY, Day of week, Duration Bucket, Rating rounded | Derived helper columns |

### Key Metrics
- Total calls: **1,000**
- Total purchase amount: **96,623**
- Average satisfaction rating: **about 3.89**
- 5-star ratings: **307**

### Sheets
- **Data** – cleaned raw data with helper columns
- **Sheet2** – pivot tables and charts that feed the dashboard
- **call center Dashboard** – final dashboard with charts and a customer-by-representative call count matrix grouped by city

### Skills Used
Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Formulas (including array formulas), Data Cleaning, Dashboard Design

---

## 2. Sales Analysis Dashboard (Power BI)

**File:** `powerbi-project/powerbi-project-1.pbix`

### Overview
A two-page Power BI report built on a star-style data model with `sales`, `people` and `locations` tables.

### Report Pages
**Page 1 – Sales Performance**
- Column chart: total sales amount by **geography**
- Bar chart: total sales amount by **team**
- Table: sales person, total amount, total boxes and amount per box (with data bars)
- Slicers for sales person and team

**Page 2 – Customer Trend**
- Line chart of **total customers** over Year → Quarter → Month → Day with a built-in **forecast** (95% confidence level)

### DAX Measures Used
`sum of amount`, `total box`, `Amount per box`, `Total customer`

### Skills Used
Data Modelling, Relationships, DAX Measures, Interactive Slicers, Drill-down Hierarchies, Forecasting, Dashboard Design

---

## How to Open the Files

- **Excel:** download `excel-project-1.xlsx` and open it in Microsoft Excel (2016 or later recommended so slicers and pivot charts work).
- **Power BI:** download `powerbi-project-1.pbix` and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).

## Screenshots

> Add your screenshots to the `screenshots/` folder and they will appear here.

![Excel Dashboard](screenshots/excel-dashboard.png)
![Power BI Dashboard](screenshots/powerbi-dashboard.png)

## Tools & Technologies
Microsoft Excel · Power BI Desktop · DAX · Pivot Tables

## Author
**Smaraki Satapathy**
B.Tech, Electronics and Communication Engineering, Silicon University, Bhubaneswar
