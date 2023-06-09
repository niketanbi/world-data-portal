# Open Data Portal

Collection of world largest data sets.

All pages
- [Employee Attrition Dataset](/employee-attrition-rate)
- [Aqi index Dataset](/aqi-by-cities)
- [World Cities Average Temperature](/content/world-cities-avg-temp)

Search or filter datasets.

<Catalog datasets = {datasets}  facets={['group']}/>



# Components available

# FlatUiTable
<FlatUiTable fullWidth url="aqicountriesData.csv" />

# Table 
<Table url="citiesAvgTemp.csv" />

# Line Chart
<LineChart 
    title = "Employee attrition at IBM"
    data = "WA_Fn-UseC_-HR-Employee-Attrition.csv"
    yAxis = "HourlyRate" 
    xAxis= "DailyRate"  
/>

