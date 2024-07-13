1.	This project involves using an ESP8266 microcontroller to fetch real-time weather data from the OpenWeatherMap API and display it on a web page. 
2.	The ESP8266 connects to a WiFi network and sets up a web server to handle HTTP requests.
3.	 The main page served by the ESP8266 includes a chart displaying temperature and humidity data, updated every 30 seconds, as well as an interactive map centered on specific latitude and longitude coordinates.
4.	 Additionally, the map allows users to click on any location to view the temperature and humidity for that specific point. The project retrieves weather data, including temperature and humidity, from the OpenWeatherMap API in JSON format.
5.	The temperature is converted from Kelvin to Celsius, and both temperature and humidity are stored in variables.
6.	These values are then provided to the web page through a JSON endpoint, which the page fetches periodically to update the displayed data. The interface is styled with Bootstrap and includes a spinner to indicate data loading, while the map uses Leaflet.js for interactive features. 
7.	This setup allows real-time monitoring of weather conditions from a specific location, displayed in a user-friendly web interface, and provides dynamic weather updates based on user interaction with the map.
