## Simple Weather forecasting Application

This is the simplest weather forecastion application created using HTML, CSS and JAVASCRIPT

Open-meteo free weather api's is used to fetch real-time weather data

* step 1 - get the geocodes (latitude & longitude) of the city.

**
    API** - https://geocoding-api.open-meteo.com/v1/search?name=${cityname}

* step 2 - use those geocodes inside open-meteo free api to get the actual weather data.

**
    API** - https://api.open-meteo.com/v1/forecast?latitude=${latitude}&longitude=${longitude}&current_weather=true
