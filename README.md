### Wheather Forecast Application

## API Info:

https://api.forecast.io/forecast/<api-key>/<latitude>,<longitude>
 
api-key: 85b0584762373b4a01ea5de2410efc0e

eg: https://api.forecast.io/forecast/85b0584762373b4a01ea5de2410efc0e/17.385044,78.486671
 
This api.forecast.io serves the complete(temperature, humidity, wind speed, summary-of-weather) weather information of location in the following stages:
1. Overall summary of weather at present
2. last hour summary at each minute
3. last day summary at each hour
It has icons-types also to enumerate the weather status.
 

## The Question is;
 
Present the weather information of a selected location as served from api.forecast.io.
  mode of selecting a location:
    1. An auto complete input box: on key up should suggest cities (at least in India).
    2. Pinned location from bing map.
 
## The weather info should contain;
1. Details of the location
2. Overall summary, last hour summary, and current days summary
3. A Icon to enumerate the summary[cloudy, rainy, clear-sky, night, hot, burning and so on] is mandatory
 
