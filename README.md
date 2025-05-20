# Metropolitan Police Monthly Crime Dashboard

<div align="center">
  <img height="200" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmtpZms0aTRxYmFrYWVzYTk3ZjZnMHBoNzJkaHcwbjJsMHo1c2tqOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lmDLeqLbOEare/giphy.gif"  />
</div>


## 📄 Overview
This project presents a data dashboard of UK Metropolitan Police monthly crime data. It outlines the process of cleaning raw crime data in Excel, importing it into SQL Server, and visualizing insights in Power BI.

## 🛠️ Tools & Technologies
- Microsoft Excel
- Microsoft SQL Server
- Power BI
- UK MPS Monthly Crime Dataset from [London Data Store](https://data.london.gov.uk/dataset/mps-monthly-crime-dahboard-data)

## 📊 Project Components
1. **Data Cleaning in Excel**
   - Replaced "Not Known"/"Not Given" values with NULLs
   - Used quartiles and IQR to detect and remove outliers

2. **SQL Server Integration**
   - Database: `LondonCrimesDB`
   - Created views to simplify data access and enhance security

3. **Power BI Visualizations**
   - Line Graph: Crime count trends over time
   - Stacked Bar Chart: Crime types comparison
   - Map: Regional crime distribution
   - KPI & Donut Charts: Crime category breakdown and totals

## 🎯 Objective
To enable clear and concise insights into London’s crime trends and patterns, helping users make informed decisions or conduct further investigations.

## ✅ Key Insights
- Domestic Abuse was the most reported crime (30%)
- Gun crimes were the least reported (1.71%)
- City of London showed the highest crime rate overall
- Time trends help spot seasonal and annual changes

## 📁 File Structure
- `Report - Task 2.pdf`: Detailed project report
- `dashboard.pbix`: Power BI file (not included here)
- `README.md`: Project documentation
