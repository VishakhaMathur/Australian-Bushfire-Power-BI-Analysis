# Australian-Bushfire-Power-BI-Analysis
## Methodology
### Project Overview
This project analyses the satellite-detected bushfire incidents occurred in Australia in the year of 2019.
The main objective of this project is to understand the geographic distribution, trends over time, and fire intensity. 


### Data Cleaning
Changed names of the attributes like acq_time to Acquisition time, acq_date to Acquisition date. The original data type of acq_date was in text. It was later converted into date format for requirement of time series analysis. This helped me to extract start and end date of the bushfire, year, month, date and day columns in the dataset. The addition of year and monthly columns gave the respective trend analysis by allowing grouping. The new month column also gave the seasonality analysis and showed which month is the most prone to bushfires. 
The confidence category was presented as a range. Hence, another column called Confidence category was added. If data is less then 30 then category is Low, if it from 31 to 69 then medium, and if 70 to 100, then High. This ensured consistent filtering, improved comparison and simplified the visualization.
Verified latitude and longitude for the accuracy of mapping. 

### KPI
Total bushfires - 5764
Start Date -  01-09-2019
End date -  31-12-2019
Average fire brightness - 326.25
High confidence fire count - 40036
Total bushfires in the following months: September - 5764, November - 21007, December - 39400 


### Trend Analysis
Trend between brightness and acquisition time suggested that brightness of bushfire was the highest at the noon and lowest around 10pm.
Analysis between average fire brightness and month name showed that December had the brightest bushfires. 
Geographic distribution of bushfires was depicted with the help of map visual. 
Intensity hotspots were displayed by using map visual.
Reliability of data was verified by using the confidence category. If it is low, then the satellite data is nearly false. If it is medium, then there could be a bushfire and if it is high, then a bushfire very likely took place. 

### Tools Used in the project
- Power BI
- Excel

### Screenshots of the KPIs and trends
(See screenshots folder)

### How to use
Download the `.pbix` file and open it using Power BI Desktop.

### Link to the dashboard
https://app.powerbi.com/groups/me/reports/a10056ff-09c4-4940-8489-e94d97b19ab3/ed4f4ab67d8919aea85a?experience=power-bi

