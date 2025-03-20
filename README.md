# AirQualityAnalysis
Analyzing LA air quality trends (2005-2024) and the impact of wildfires and other pollutants to project future air quality levels.

## Data Sources
- **Air Quality Data:** https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual

## Process
- Compiled air quality data from 2004-2024
- Filtered for LA County using SQL to show the last 20 years of data (2005-2024)
  
## SQL Query
```sql
SELECT *
FROM "LA Air Quality Project - Verison 1"
WHERE county = 'Los Angeles' AND year !=2004;
```

## Next Steps
- Integrate wildfires and pollution datasets
- Conduct deeper trend analysis
- Create visualizations and forecasts
