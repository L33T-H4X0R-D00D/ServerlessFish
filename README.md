# ServerlessFish
Fish predictions
v 0.14




# Requirements
* Collect information from API at predetermined intervals.
* Store collected data in DB or similar including the actual data and the time the data was collected.
* Decision: Create data map or overwrite forecast data with higher weighted (newer) data. 
* Regular clean up truncating data for events in the past and underweight data.



# Required data
* Temperature -
* Estimated water temp -
* Cloud cover -
* Wind - 
* Barometric Pressure -  https://github.com/attack/barometer
* Tides/Moonphases -
* Precipitiation -
* Hatch dates and types -
* Fish breeding patterns -

Assign each data type a rating of 1 to 4.  Take mean of all data types for the overall rating for the day. 


# User story

User provides location data (City, zip, etc), app returns html calendar showing grade for each item tracked and cumulative grade. Show UUID based on newest data date to ensure users understand when newest data has been added to prediction.



# References 
* https://bfaht.com/fishing/calendar/22602/9/2023
* https://solunarforecast.com/hunting_fishing/best_times/zip_postal_code/chart/us/22602

Keep variable for active zip codes.  Zipcodes hit in the last 30 days.  Once they've aged out remove them from the active zip codes variable to save API call costs. 









From ChatGPT:

Temperature: Many freshwater fish are more active in moderate temperatures. As a general rule, early morning and late afternoon tend to be better times for fishing. Fish are often more active in cooler temperatures.
Cloud Cover: Overcast or cloudy days can be advantageous for fishing. Cloud cover reduces the amount of sunlight penetrating the water, making fish less cautious and more likely to venture into shallower areas.
Wind: A gentle breeze or light wind can be beneficial. It can help to break up the surface of the water, making it harder for fish to see you. However, excessively strong winds can make fishing difficult. A gentle breeze can be beneficial as it oxygenates the water and makes fish less wary.
Barometric Pressure: Many suggest that stable or falling pressure is better than a rising barometer.
Rain: Light rain can also be good for fishing. It can create a feeding frenzy among fish as raindrops hitting the water mimic the sound of insects falling.
Seasonal Considerations: Different seasons can affect fishing conditions. For example, in spring, fish may be more active as they prepare for spawning. In winter, fish might be more lethargic and found in deeper, warmer waters.
Clear water conditions can make fish more cautious, requiring a more stealthy approach and the use of lighter lines. In murky water, fish may be less wary, and lures with more vibration and color may be effective.

Moon phase:
Full Moon: Many anglers associate the full moon with increased fish activity. Some species, such as walleye and catfish, are believed to feed more actively during the night under a full moon. The bright moonlight can make it easier for predators to locate prey.
New Moon: A new moon, when the moon is not visible in the night sky, is often associated with darker nights. Some anglers believe this makes fish less wary and more willing to move into shallower areas to feed. During a new moon, predators may rely more on their other senses, such as smell and vibration, to locate prey. 
First and Last Quarter: Some anglers consider the periods around the first and last quarter moon phases to be good times for fishing. These phases are associated with moderate moonlight, which may encourage fish to feed.
Changing Moon Phases: The transitions between moon phases, such as the waxing and waning crescent phases, are thought by some anglers to trigger fish activity. These transitions are often associated with changes in barometric pressure.

Fishing the hatch:
Mayflies:
Species: Various mayfly species are found in the mid-Atlantic, including Blue Winged Olives (BWO), Hendricksons, and Sulphurs.
Hatch Period: Mayflies typically hatch in the spring and early summer.
Fishing Tips: Matching the size, color, and profile of the hatching mayflies is crucial. Patterns like Blue Winged Olive and Sulphur imitations are popular.

Caddisflies:
Species: Caddisflies are abundant, and species like the Green Sedge and Spotted Sedge are common.
Hatch Period: Caddisflies can hatch throughout the fishing season, with peaks in spring and early summer.
Fishing Tips: Caddisfly patterns in various sizes and colors are effective. The Elk Hair Caddis is a classic pattern for imitating adult caddisflies.

Stoneflies:
Species: Common stonefly species include the Little Black Stonefly and the Golden Stonefly.
Hatch Period: Stoneflies typically hatch in the early to mid-spring.
Fishing Tips: Stonefly nymphs and adult imitations can be effective during their respective life stages.

Midges:
Species: Midges are prevalent year-round, making them an important food source.
Hatch Period: Midges can hatch in any season, but they are particularly important in the colder months.
Fishing Tips: Small midge patterns, both larvae and adults, are effective, especially in winter.

Terrestrial Insects:
Species: Beetles, ants, and grasshoppers are important terrestrials.
Hatch Period: Terrestrials are active in the warmer months, with beetles and ants being common in late spring and summer.
Fishing Tips: Use patterns that imitate terrestrial insects falling into the water, as they can be a significant food source for fish.

Dragonflies and Damselflies:
These larger insects can be important for anglers targeting warmwater species in ponds and lakes.

Moths:
Moths can also be significant, and patterns imitating moth larvae or adult stages may be effective.

Beetles:
Beetles are common terrestrial insects and are particularly effective during the summer months.

Grasshoppers:
Grasshoppers are abundant in many areas and can be a major food source for fish during the warmer months.

Diptera (True Flies):
Various species of true flies, including black flies and crane flies, can be important in different water systems.
