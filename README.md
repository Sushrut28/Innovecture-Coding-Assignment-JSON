# Innovecture-Coding-Assignment-JSON

Application is built using spring boot.

Can enter any US zip code for ex. 67301 and API will return the coolest hour of next day.

Coolest hour API : http://localhost:8080/forecast/zipcode?zipcode=67301

Above API will return JSON
{
  "city": {
    "name": "Independence",
    "country": "US"
  },
  "list": [
    {
      "main": {
        "temp": "280.35",
        "temp_min": "280.35",
        "temp_max": "280.35",
        "date": "2021-11-07",
        "coolestHour": "12:00:00"
      }
    }
  ],
  "message": "0"
}
