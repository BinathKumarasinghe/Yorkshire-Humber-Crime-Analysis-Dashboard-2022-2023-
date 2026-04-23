# Yorkshire-Humber-Crime-Analysis
🚔Yorkshire & Humber Crime Analysis Dashboard

📌 Overview

This project analyzes crime data from the Yorkshire & Humber region using SQL Server and Power BI. The goal is to transform raw police datasets into meaningful insights through data cleaning, modeling, and visualization.

📂 Dataset

Source: UK Police Open Data (https://data.police.uk/
)
Time Period: 2022–2023
Total Files: 264 datasets
Categories:
Street Crime
Stop and Search
Crime Outcomes

⚙️ Tools & Technologies

SQL Server Management Studio (SSMS)
Power BI
DAX (Data Analysis Expressions)

🧹 Data Processing

Imported datasets manually into SQL Server
Consolidated into 3 main tables:
StreetCrime
StopAndSearch
CrimeOutcomes
Removed duplicates using CTE and ROW_NUMBER()
Handled null values:
Text fields → "Unknown"
Numeric fields → 0
Database backup created before visualization

📈 Dashboard Features

Interactive navigation with filters (Year, Region)
Visual breakdowns of:
Crime types
Monthly & seasonal trends
Geographic distribution
Demographics (age, gender, ethnicity)
Key KPIs using DAX (e.g., most common crime percentage)
Map visualizations filtered for valid coordinates

🔍 Key Insights

Violent & sexual offenses ≈ 40% of total crimes
High percentage of cases result in no prosecution (38%–44%)
Stop & search:
~63K incidents
Only ~16% lead to arrests
Crime is concentrated in West Yorkshire
Seasonal patterns show peaks during summer months

📌 Conclusion

This project demonstrates how data analytics can support law enforcement and policymakers by identifying trends, inefficiencies, and high-risk areas. The dashboard provides a foundation for improving crime prevention strategies and resource allocation.
