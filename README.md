# Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is a data analytics project developed using Microsoft Power BI to analyze Uber trip data and identify insights related to bookings, booking value, trip distance, trip duration, time-based demand, and pickup locations.

The dashboard contains three interactive pages that help users explore trip performance, understand booking patterns, compare vehicle types, and examine individual trip records.

## 🎯 Project Objectives

- Analyze total bookings and booking value.
- Understand trip distance and average trip duration.
- Identify booking patterns across different days and times.
- Compare performance across vehicle types and payment methods.
- Identify the most frequent pickup and drop-off locations.
- Explore detailed trip records using an interactive table.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and visualization
- **DAX (Data Analysis Expressions)** — Measures and dynamic calculations
- **Data Modeling** — Relationships between trip and location data
- **Power Query** — Data preparation and transformation, if used in the project

## 📊 Dashboard Pages

### 1. Overview Analysis

This page provides a summary of overall trip performance through key performance indicators (KPIs) and visualizations.

**Key Performance Indicators**
- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Time
- Average Trip Distance

**Visualizations and Insights**
- Dynamic measure selector for Total Bookings, Total Booking Value, and Total Trip Distance
- Booking analysis by payment type
- Day and night trip comparison
- Vehicle type performance analysis
- Daily booking trends
- Most frequent pickup and drop-off points
- Farthest trip analysis
- Total bookings by location
- Most preferred vehicle by pickup location

**Screenshot:**

![Overview Analysis](Dashboard%20page%201.png)

### 2. Time Analysis

This page focuses on understanding how trip activity changes throughout the day and across different days of the week.

**Visualizations and Insights**
- Trip distance by pickup time
- Trip distance by day of the week
- Hour-by-weekday heatmap covering hours 0–23 and Monday–Sunday
- Dynamic measure selector for comparing booking-related metrics
- Time-based demand patterns to identify busier and quieter periods

These visualizations help users explore when trip activity is higher and how demand varies by time and weekday.

**Screenshot:**

![Time Analysis](Dashboard%20Page%202.png)

### 3. Details

This page presents individual trip records in a detailed tabular format for further analysis.

**Details Included**
- Trip ID
- Pickup Date
- Pickup Hour
- Vehicle Type
- Payment Type
- Number of Passengers
- Trip Distance
- Booking Value
- Pickup Location
- Total Bookings

The table allows users to inspect trip-level information and explore the data behind the dashboard's summarized results.

**Screenshot:**

![Details](Dashboard%20Page%203.png)

## 📈 Key Insights Supported by the Dashboard

The dashboard enables users to investigate:

- Overall booking volume and booking value.
- Differences in trip patterns across vehicle types.
- Payment method distribution.
- Trip activity by time of day and weekday.
- Locations with higher booking volumes.
- Variations in trip distance and duration.

Actual business conclusions should be drawn from the selected filters and the underlying dataset.

## ⚙️ Key Features

- Three-page interactive Power BI report
- KPI cards for quick performance monitoring
- Dynamic measure selection
- Date and city filtering
- Vehicle and payment analysis
- Location-based insights
- Time-based visualizations
- Detailed trip-level data table

## 📂 Project Structure

```text
Uber-Trip-Analysis-Dashboard/
│
├── README.md
├── uber trip dashboard.pbix
├── Uber_Trip_Analysis_Dashboard_project.pdf
├── Dashboard page 1.png
├── Dashboard Page 2.png
├── Dashboard Page 3.png
├── Location Table.xlsx
└── Uber Trip Details.xlsx
```

*The file names above reflect the project files currently included in the repository. Update this structure if you rename or move files.*

## 🚀 How to View the Project

1. Open the GitHub repository.
2. Review the README and dashboard screenshots.
3. Download the `.pbix` file.
4. Open the downloaded file using Microsoft Power BI Desktop.
5. Navigate through the Overview Analysis, Time Analysis, and Details pages.
6. Use the available slicers and interactive visuals to explore the report.

## 💡 Conclusion

This project demonstrates the use of Power BI to transform trip-level data into an interactive analytics dashboard. It combines KPI monitoring, time-based analysis, vehicle comparisons, location insights, and detailed records in one report.

The project showcases practical skills in data visualization, DAX measures, data modeling, and dashboard design.

---

**Project Type:** Data Analytics  
**Domain:** Transportation Analytics  
**Tool:** Microsoft Power BI  
**Author:** Disha Tangadkar
