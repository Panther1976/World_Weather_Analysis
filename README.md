# World_Weather_Analysis

## Background

The purpose of this project is to add the weather description to the weather data as part of the PlanMyTip app. Based on the input from beta testers the data will be filtered for their weather preferences. This will be utilized to search for and list travel destinations that meet the criteria provided. Four cities will then be chosen and with the help from Google Maps Directions API, a route will be created with a marker layer map. 

After generating a list of 2,000 random latitudes and longitudes, a list was compiled of the nearest city for each combination and the following data was retrieved using an API call:

-	Latitude and longitude
-	Maximum temperature
-	Percent humidity
-	Percent cloudiness
-	Wind speed
-	Weather description (for example, clouds, fog, light rain, clear sky)

Below is a sample of the weather data collected.

<img width="416" alt="Deliverable1_df_head" src="https://user-images.githubusercontent.com/106631875/202645924-144f6f88-f42f-41d7-bb37-b8c531aade73.png">

