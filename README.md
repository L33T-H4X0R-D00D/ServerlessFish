# ServerlessFish
Fish predictions
v 0.12




# Requirements
* Collect information from API at predetermined intervals.
* Store collected data in DB or similar including the actual data and the time the data was collected.
* Decision: Create data map or overwrite forecast data with higher weighted (newer) data. 
* Regular clean up truncating data for events in the past and underweight data.



# Required data
* Temperature -
* Estimated water temp -
* Barometric Pressure -
* Tides/Moonphases -
* Precipitiation -
* Hatch dates and types -
* Fish breeding patterns -




# User story

User provides location data (City, zip, etc), app returns html calendar showing grade for each item tracked and cumulative grade. Show UUID based on newest data date to ensure users understand when newest data has been added to prediction.



# References 
* https://bfaht.com/fishing/calendar/22602/9/2023
* https://solunarforecast.com/hunting_fishing/best_times/zip_postal_code/chart/us/22602
