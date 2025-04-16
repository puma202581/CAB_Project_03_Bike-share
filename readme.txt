The original csv file for with 10Mil+ bike ride records from the Capital Bikeshare scheme spanning over the years from 2021 to 2023 is included in the uploaded files due to memory space constraints.
My focus was on the year 2023. The ipynb files uploaded on Github show the aggregation at annual and at weekly level and by station (both). 

I included bike station capacity data from opendata.dc.gov.

I used geopy to create features like distance-to-city-centre and elevation.

With the help of ChatGPT, I then created additional features like distance-to-city-centre, proximity to residential areas, offices, venues, attractions and metrorail stations. Each time I prompted ChatGPT to generate an output of the top 20 locations (number of visitors, employees, etc.). I then calculated how many of these feature locations are within 500m of each bike station. 

This feature creation was done in order to aid the prediction of my main KPIs: imbalance and turnover.

I then used Machine Learning (Univariate and Multivariate) to identify the best model, feature combination, hyperparameter setting to predict both KPIs.

The summary of my findings can be found in the presentation file: CapitalBikeShare_presentation_PULSMarc_20250403.



  


   