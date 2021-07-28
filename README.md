# World Weather Analysis with Python & API

PlanMyTrip app is a top travel technology company that specializes in internet related services in the Hotel and Lodging industry. Jack is the head of analysis for the user interface team. I have been helping Jack to collect and present data for customers based on their preferred criteria. 

**There are three sections in this project. **

## 1.	Create Weather Database
-	 In this section, I generated 2000 pair of latitudes and longitudes and identified 768 cities from the coordinates.
-	 Using citipy API, I tried to scrape the following information for each city: latitudes & longitudes, max temperature, humidity, cloudiness, wind speed, weather description and country. Eventually, I successfully gathered information for 703 out of the 768 cities, put them into a DataFrame and exported to a csv file.

The [Weather_DataBase.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Weather_Database/Weather_Database.ipynb) file
The [WeatherPy_Database.csv](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Weather_Database/WeatherPy_Database.csv) file


## 2.	Vacation Search
-	 703 cities are narrowed down to 257 cities by applying a preference criterion: min and max temperature. 
-	 Using gmaps API, I found a hotel nearby each city and created a DataFrame to hold destination information and the hotel name. The DataFrame was exported as a csv file.
-	 A map with marker and info box is generated for the vacation search. 

The [Vacation_Search.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/Vacation_Search.ipynb) file
The [WeatherPy_vacation.csv](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/WeatherPy_vacation.csv) file
The [WeatherPy_vacation_map.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/WeatherPy_vacation_map.png) image


## 3.	Vacation Itinerary
-	 Finally, four cities were chosen to create a final travel itinerary. Start & end: Xuanzhou; stop1: Pingdingshan; stop2: Hanzhong; stop3: Yongan.
-	 By using the Google Maps Directions API, I created a travel route by driving between the four cities within marker layer map.
-	 Lastly, map with marker and info box for only these four cities was created and exported.

The [Vacation_Itinerary.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/Vacation_Itinerary.ipynb) file
The [WeatherPy_travel_map.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/WeatherPy_travel_map.png) image
The [WeatherPy_travel_map_markers.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/WeatherPy_travel_map_markers.png) image

