# ca-covid-map
The data in countystatus.json is a snapshot from 9/1/2020.  This appears to be a static asset hosted at `https://covid19.ca.gov/countystatus.json`.  You will not be able to access this directly from your application.

You can however create a crontab job that runs the following:  `wget https://covid19.ca.gov/countystatus.json` as long as countystatus.json and index.html reside in the same folder you should be good to go.

![ca-covid-map application screenshot](https://github.com/Paul-Hoke/ca-covid-map/blob/master/ca-covid-map-screenshot.PNG "Screenshot")

![ca-covid-map rates](https://github.com/Paul-Hoke/ca-covid-map/blob/master/ca-covid-map-rates.PNG "rates table")
