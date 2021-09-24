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

-------------

### API Description

* MovieDB, [link to it](https://www.themoviedb.org/) provides a collection of movies, TV shows and actor data. 

### Usage

* In city explorer i used this API for getting the movies and shows that related/same as the city name that the user want to search about.
 
### API Endpoints/Request URLs

* in city explorer i used ```/search``` end points and this is a sample request url:
```https://api.themoviedb.org/3/search/movie?api_key={api_key}&query=Jack+Reacher```

### Authentication Key

* API Key Access Tokens