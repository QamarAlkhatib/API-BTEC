# Designing and Implementing an application that incorporates relevant APIs

* Investigate appropriate APIs for the City Explorer System.

* In city explorer project I used these 3 APIs:

### API Description

* LocationIQ, [link to it](https://locationiq.com/) provides flexible enterprise-grade location based solutions.

### Usage

* this one helped my project to get the Geocoding and maps picture for each city in the world. by searching only for the name of city/country.

### API Endpoints/Request URLs

* LOcation IQ was having 2 endpoints. In US ans EU. the one i used is ```/search```

* in city explorer the endpoint was in EU and the request URL was
```https://eu1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json```

### Authentication Key

* Using Access Tokens.
* Key: pk.a0fd29311853789b83630c120d292f03

----------------------
### API Description

* Weatherbit, [link to it](https://www.weatherbit.io/api) provides weather information for future,past and the current weather data. and this can be done in many ways such as searching by city name, city ID, Latitude/longitude etc. 

### Usage

* in city explorer i used this API to retrieve the weather for forecast API (16day / daily) with searching by city name feature.

### API Endpoints/Request URLs

* EndPoints: searching by city name, city ID, Latitude/longitude, postal code, and station. and in city explorer was searching by city name. Endpoint: ```/forecast/daily?```

* Request URL sample: 
```https://api.weatherbit.io/v2.0/forecast/daily?city=Raleigh,NC&key=API_KEY```


### Authentication Key

* API master Key (Access Tokens)
* Key: 2838128258f14da4a8b2d5064dd19e7c

-------------

### API Description

* MovieDB, [link to it](https://www.themoviedb.org/) provides a collection of movies, TV shows and actor data. 

### Usage

* In city explorer i used this API for getting the movies and shows that related/same as the city name that the user want to search about.
 
### API Endpoints/Request URLs

* in city explorer i used ```/search``` end points and this is a sample request url:
```https://api.themoviedb.org/3/search/movie?api_key={api_key}&query=Jack+Reacher```

### Authentication Key

* API Key Access Tokens.
* Key: 54cc9f2eb55ebbd8b733256bd764b01a

---

## Link To my Live URL:

### [City-Explorer](https://deploy-preview-15--city-explorer-qamar.netlify.app/?utm_source=github&utm_campaign=bot_dp) 
https://deploy-preview-15--city-explorer-qamar.netlify.app/?utm_source=github&utm_campaign=bot_dp 

### [Heroku](https://city-explorer-class07.herokuapp.com/) 
https://city-explorer-class07.herokuapp.com/

### [Backend Repo](https://github.com/QamarAlkhatib/city-explorer-api) 
https://github.com/QamarAlkhatib/city-explorer-api

### [Frontend Repo](https://github.com/QamarAlkhatib/city-explorer) 
https://github.com/QamarAlkhatib/city-explorer
