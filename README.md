# WeatherApp
This Java application was developed as part of the 'Advanced Object and Functional Programming' course during the third semester of my studies at Warsaw University of Technology. The application provides users with the ability to view current, historical, and forecasted weather data for a selected location on a world map.

### Key features of the application include:

- Displaying current weather conditions
- Changing weather units (Celsius/Fahrenheit, etc.)
- Selecting a time range for weather data visualization
- Dynamically updating weather charts
- Saving weather data to a PDF file
- Displaying the name of the selected location on the map
  
Each time a user selects a point on the map, chooses a weather type, and sets the desired time range, weather data is fetched through an API request from Open Meteo API ([https://open-meteo.com/](https://open-meteo.com/)). The name of the selected location is retrieved and displayed using Nominatim ([https://nominatim.org/](https://nominatim.org/)).

The application utilizes the Java component JMapViewer to display the map. The project is based on the Maven structure and the graphical user interface is built using the Swing library.

### Authors

- [Miłosz Zieliński](https://github.com/zielinskim04)
- [Ada Wojterska](https://github.com/adawojterska)
