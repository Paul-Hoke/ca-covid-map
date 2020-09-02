# ca-covid-map
The data in countystatus.json is a snapshot from 9/1/2020.  This appears to be a static asset hosted at `https://covid19.ca.gov/countystatus.json`.

This can be hosted on any webserver.  Simply create a cronjob - `wget https://covid19.ca.gov/countystatus.json` to update the data and you are good to go.

![ca-covid-map application screenshot](ca-covid-map-screenshot.png?raw=true "Screenshot")
