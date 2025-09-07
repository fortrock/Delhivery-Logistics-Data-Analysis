# Logistics Delivery Data Analysis – Power BI

## Overview
This Power BI project provides an exploratory data analysis (EDA) of logistics delivery performance, focusing on shipment volumes, delivery times, distance coverage, and delay trends.

## Key Metrics
- **Total Shipments:** 144,870
- **Total Distance Covered:** 33.91M units
- **Average Delivery Time:** 416.93 (unit based on dataset – minutes/hours)
- **On-Time Deliveries:** 81.97%
- **Delayed Shipments:** 18.03%

## Visualizations
- **Cutoff Analysis** – Identifies cutoff compliance and missed cutoffs.
- **Route Type Distribution** – Compares Full Truck Load (FTL) vs Carting.
- **OSRM vs Actual Time & Distance** – Evaluates route optimization accuracy.
- **Shipment Trends Over Time** – Tracks delivery volumes across weeks.
- **Start-to-End Scan Distance** – Measures scanning delay distribution.
- **Day & Time Analysis of Complaints** – Highlights peak problem periods.

## Data Source
- Table: **delhivery**
- Contains fields for shipment time, distance, route type, day of week, scan times, and delay indicators.

## Insights
- Majority of shipments are delivered on time (~82%).
- Around 18% shipments experience delays, often linked to cutoff violations.
- Peak complaint days: **Friday & Sunday**.
- Significant deviation between OSRM-predicted and actual distances on some routes.

## How to Use
1. Download `LOGISTICS.pbix` from this repository.
2. Open using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Refresh data if connected to your live source.
4. Explore KPIs using built-in filters and slicers.

## Future Enhancements
- Integrate predictive delay analytics (ML model).
- Add real-time delivery tracking APIs.
- Include cost per route and carbon footprint KPIs.
