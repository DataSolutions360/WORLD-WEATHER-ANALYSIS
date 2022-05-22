# WORLD-WEATHER-ANALYSIS

# Overview

Using the APIs(Application Program Interface) of OpenWeatherMap, I was tasked with adding weather description 
to indices of the soon-to-be-referenced DataFrame.  This is used to to provide criteria for potential 
trip planner agendas for beta testing.

Followed up with Google Maps API, with start and stop points for each destination within a "road trip", 
I created routes and maps for travelers to decided where they want to go and stay, in hotels.

# Results

## Deliverable 1

For Deliverable 1, the task was to retrieve 2000 different, randomly generated, latitude and longitude 
coordinates using API calls from OpenWeatherMap.  The data that was called also included the information on
cities that reside in the longitudes and latitudes that was randomly gathered, as well as max temperature, 
and weather description.  New DataFrames were suquentially created to suit referential needs.

![image](https://user-images.githubusercontent.com/8845050/169702537-a8d7a735-4048-4f98-b097-2335f938780d.png)

The above code produced the DataFrame which supported the below extract(csv), which will be later referenced in 
Deliverable 2.

![image](https://user-images.githubusercontent.com/8845050/169702566-4dbd9e57-e683-4ac1-af18-7456c028b878.png)

## Deliverable 2
Google Cloud Platform was utilized to identify potential travel destinations and potential hotels for travelers.  
Hotels were added as markers around the world in order to give travelers options 

![RUSSIA](https://user-images.githubusercontent.com/8845050/169706339-2cd8b5f6-28d2-4108-b036-efe7f92685b8.png)

## Deliverable 3
Google Directions API was used to create a travel itinerary  showing a road trip route.  As you can see, the group 
did not plan the most logistically sound, sequentially organized, route.  After carefully discussing with them to
re-arrange the order of the destinations, they explained that they were going to a wedding, which explains the 
inefficiency in the route below.

![image](https://user-images.githubusercontent.com/8845050/169706429-e6288d98-46ed-4653-a883-3337fbca993f.png)

# Resources
- Python 3
- OpenWeatherMap
- Google CLoud Platofrm
- Jupyter Notebook
- Pandas
- Anaconda 




