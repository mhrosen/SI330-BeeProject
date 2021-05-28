# SI330-BeeProject

## Instructions 
<em>Before running the code you must:</em>
1. Request a username and password from https://docs.quandl.com/docs/in-depth-usage
2. Create a passwords.csv file with the API key to project folder
3. Change the variable source_dir to represent your directory path
<br>

## Description
- Explored whether changes in the US bee population, represented by the reported number of commercial bee colonies, could affect the supply of bee-pollinated produce and price indexes overtime compared to that of control commodities.

- Combined 4 data sets, including 3 CSV and 1 API with Pandas and Python, caching results with requests-cache to reduce strain on API server.  

- Standardized comparable data metrics (i.e. US dollars, dollars/pound, financial quarters) and calculated the percent change year-over-year.

- Visualized time series plots of percent change and raw values of commodity indices, honey prices, and market controls against respective bee colony population trends.
