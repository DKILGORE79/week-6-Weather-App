# Weather Dashboard

## Server-side API: Weather Dashboard

The application is a weather dashboard that uses the openweathermap api to acquire weather data for the current day as well as the five day forecast and presents them to the user in a user friendly format on the user interface.

Upon Loading the user is presented with a search icon that reveals an input area when clicked. If the user has previous searches saved in local storage then the user is also presented with a list of the 8 most recent searches, which the user can click to get the weather data for the selected city. The user can also type in a new city into the search input and upon hitting enter key the data is presented.

### Data Outputs

the application provides the user with the following:

- Search History
- Current Weather forecast with the city, date, weather icon, word description of the forecast, temperature, humidity, wind speed and UV index (The UV index is color coded and a scale is also presented to help the user identify the severity of the UV index).
- Five day forecast with the date, weather icon, temperature and humidity

**IMAGES**
![](/assets/images/preview_1.png) ![](/assets/images/preview_2.png) ![](/assets/images/preview_3.png)

### APIs used to power Application

[www.openweathermap.org]

[https://api.openweathermap.org/data/2.5/weather?q={city-name}&appid={your-api-key}]

[https://api.openweathermap.org/data/2.5/forecast?q={city-name}&appid={your-api-key}]

[https://api.openweathermap.org/data/2.5/uvi?appid={appid}&lat={lat}&lon={lon}]

## Resources used

- https://ileriayo.github.io/markdown-badges/
- https://fontawesome.com/v5/icons/save?s=solid
- https://developer.mozilla.org/en-US/docs/Web/API/Storage/getItem -https://stackabuse.com/storing-data-in-the-browser-with-localstorage/
- Leah Green-Fullbrightness production - tudor
- normalized css by github.com/necolas/normalize.css
- Reset.css by Eric Meyers http://meyerweb.com/eric/tools/css/reset/

## Contributor:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

## License

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
