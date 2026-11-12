# Tata Motors Sales Analysis Dashboard

An interactive 3-page Power BI dashboard built on 4,800 Tata Motors sales records (Jan 2024 to Jun 2026). Python was used to clean and verify the data, Power Query to shape it, and DAX to build the measures.

## Dashboard Preview

### Overview
![Overview](screenshots/01-overview.png)

### Detailed Sales Report
![Detailed Sales Report](screenshots/02-detailed-sales-report.png)

### About Project
![About Project](screenshots/03-about-project.png)

## Tools Used
<!-- ----------------------------------------- -->
- Python (data cleaning and checking)
- Microsoft Power BI Desktop
- Power Query
- DAX
<!-- ----------------------------------------- -->

## Dataset

- 4,800 sales records, Jan 2024 to Jun 2026
- Columns include Year, Month, State, Region, Vehicle Category, Vehicle Model, Fuel Type, Units Sold, Revenue and Satisfaction Score
- 2026 data covers January to June only

## Key Metrics
<!-- ----------------------------------------- -->
| Metric                | Value         |
|-----------------------|---------------|
| Total Units Sold      | 62,881        |
| Total Revenue         | Rs 10,994 Cr  |
| Total Sales Records   | 4,800         |
| Average Satisfaction  | 8.5 / 10      |

## Dashboard Features

- KPI cards for units, revenue, records and satisfaction
- Yearly and monthly sales trends
- Vehicle category performance (donut chart)
- Top 10 states by revenue and top 10 vehicle models by units sold
- Regional model ranking (top model per region)
- Slicers for Year, Region, State and Vehicle Category
- Page navigation buttons between all three pages
- Detailed table with all sales records

## Key Insights

- EV is the top category with 24.9% of total units, followed by SUV (20.0%).
- Punch EV is the best-selling model with 3,071 units.
- Karnataka leads revenue with Rs 1,179 Cr; Uttar Pradesh is lowest at Rs 984 Cr.
- Trucks generate the most revenue (Rs 3,166 Cr, about 29% of total).
- East and South regions bring the most revenue; West and North are behind.
- Units grew 1.4% in 2025 vs 2024 (2026 data covers Jan to Jun only).

## Project Structure
<!-- ------------------------------------------------- -->
tata-motors-sales-dashboard/                    
dashboard/ Power BI file (Tata_Motors.pbix)     
data/ Cleaned dataset (tata_motors_cleaned.csv) 
python/ Jupyter notebook used for data checking 
screenshots/ Dashboard page screenshots         
<!-- ------------------------------------------------- -->


## How to Open

1. Download `dashboard/Tata_Motors.pbix`.
2. Open it in Power BI Desktop (free download from Microsoft).

## Author

Amar Sarode
