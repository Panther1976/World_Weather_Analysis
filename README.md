# World_Weather_Analysis

## Background

The purpose of this project is to add the weather description to the weather data as part of the PlanMyTip app. Based on the input from beta testers the data will be filtered for their weather preferences. This will be utilized to search for and list travel destinations that meet the criteria provided. Four cities will then be chosen and with the help from Google Maps Directions API, a route will be created with a marker layer map. 

### Deliverable 1

After generating a list of 2,000 random latitudes and longitudes, a list was compiled of the nearest city for each combination and the following data was retrieved using an API call:

-	Latitude and longitude
-	Maximum temperature
-	Percent humidity
-	Percent cloudiness
-	Wind speed
-	Weather description (for example, clouds, fog, light rain, clear sky)

Below is a sample of the weather data collected.

<img width="416" alt="Deliverable1_df_head" src="https://user-images.githubusercontent.com/106631875/202645924-144f6f88-f42f-41d7-bb37-b8c531aade73.png">

### Deliverable 2

In Deliverable 2 the beta tester is asked to input the minimum and maximum temperatures for the potential destinations. The data below is a sample collected based on that input:

<img width="464" alt="Deliverable2_df_head" src="https://user-images.githubusercontent.com/106631875/202650749-9663e2b3-77d2-4b4c-9acb-4b4392b9caae.png">

Based on the list of cities above a new dataframe is created with the names of nearby hotels. If there is a hotel isn't found, that city is later dropped from the list. Below is a sample of the data collected:

<img width="388" alt="Deliverable2_hotels" src="https://user-images.githubusercontent.com/106631875/202651347-2e2c43e7-a0ed-4811-a52b-2703986e69ab.png">

Based on the hotel information from above, a marker layer map was created and can be seen below:

<img width="408" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/106631875/202651714-1a236cc5-8788-48db-93a4-363eb039224d.png">

### Deliverable 3

Based on the map created in deliverable 2, four cities are selected that are relatively close together and a vacation itinerary is created with a propsed route. See below:

<img width="363" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/106631875/202652911-02ed75a7-9994-4d08-b8b9-b661ab907fc0.png">

Below is a picture of the cities from above with pop-up markers:

<img width="648" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/106631875/202653069-8b821a82-901e-41b6-8072-68f0dd5b2623.png">
