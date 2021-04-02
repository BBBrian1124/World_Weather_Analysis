# World_Weather_Analysis
UofT Data Analytics Boot Camp - Module 6 - APIs

# Three folders are attached in this directory
# Weather_Database
* Randomly generates a list of 2000 co-ordinates and using the citypy module we will obtain the city name
* Using the OpenWeatherMap API we will obtain weather information for that city and place it into a DataFrame and export it to a CSV
# Vacation_Search
* Load in the CSV file above and prompt the user to specify their min and max tempature for a vacation destination/city
* We will return the filtered and clean results into a DataFrame and export it to a CSV
* Using Google Places API, we will display the first search result for hotels on that city on a map with markers showing additional weather information 
# Vacation_Itinerary 
* Load in the CSV with the filtered results 
* We will use the Google Directions API to display 4 cities within the filtered DataFrame that can be visted and display the route on a map
* We will also create another map with markers for those cities showing additional weather information
