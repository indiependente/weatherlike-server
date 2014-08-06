weatherlike-server
==================

REST JSON API Weather Forecast Server using weatherlike

##Server REST APIs
- `/weatherapi/city` e.g. `/weatherapi/city?city=Rome`
- `/weatherapi/woeid` e.g. `/weatherapi/woeid?woeid=721943`

##Example Output
- WOEID http://en.wikipedia.org/wiki/GeoPlanet
- 5 days weather forecast
```json
{"woeid":"721943","forecast":[{"code":"32","date":"6 Aug 2014","day":"Wed","high":"87","low":"67","text":"Sunny"},{"code":"32","date":"7 Aug 2014","day":"Thu","high":"90","low":"68","text":"Sunny"},{"code":"32","date":"8 Aug 2014","day":"Fri","high":"88","low":"69","text":"Sunny"},{"code":"32","date":"9 Aug 2014","day":"Sat","high":"87","low":"68","text":"Sunny"},{"code":"34","date":"10 Aug 2014","day":"Sun","high":"89","low":"69","text":"Mostly Sunny"}]}
```
