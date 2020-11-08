# CrimeForecast

The City of Vancouver (Canada) has 675,218 people (2017) and the Greater Vancouver Area is the third-largest metropolitan area in Canada and is one of the Top 10 worldwide cities for quality of life. I will explore if it's possible to accurately predict the number of daily crimes in the city of Vancouver by using the Python package called [Prophet] (https://facebook.github.io/prophet/), developed by Facebook in 2017 by the Core Data Science team.


__Jupyter Notebook and Report:__

 - __Carolina_Santos_Capstone.ipynb__: Jupyter notebook with EDA and forecast.
	
 - __Carolina_Santos_Final_Report.pdf__: Report summarizing the processes and the finding on the forecasting study.
	
__Data__: 
 
 - ___crimedata_csv_all_years.csv___ - data downloaded from the VPD Geodash website <https://geodash.vpd.ca/opendata/>
		
 - ___local-area-boundary.geojson___ - data set containing the boundaries for the City's 22 local areas (also known as local planning areas) <https://opendata.vancouver.ca/explore/dataset/local-area-boundary/information/>
	
__Output Files__ 

- ___crimedata_by_neighbourhood.csv___ - data with the crimes and standardized neighbourhood
	
- ___crimedata_w_date_time.csv___ - crime data with the date time columns concatenated and in the date format for analysis on Tableau and Prophet forecasting. 
