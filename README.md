# Project 3: Sharing Dataset on Kaggle

## Description

Datasets of aircraft operated by Saudi Arabian Airlines scraped from the official Saudia website. One dataset includes info regarding the type of aircraft and number in operation, the other dataset includes detailed info regarding the different configurations for each aircraft in the Saudia fleet.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**aircraft_name**|*string*|fleet/aircraft_configs|The name of the aircraft operated|
|**number_in_fleet**|*int*|fleet|The number of planes of this type operated by the airline|
|**number_of_configurations**|*int*|fleet|The number of different configurations for that specific aircraft type|
|**configurations_links**|*string*|fleet|The url of the page where configuration data was scraped for that specific aircraft|
|**configuration_name**|*string*|aircraft_configs|The name of the configuration as per Saudia website|
|**length_in_m**|*int*|aircraft_configs|The aircraft length as per Saudia website|
|**wingspan_in_m**|*int*|aircraft_configs|The aircraft wingspan as per Saudia website|
|**range_in_km**|*int*|aircraft_configs|The aircraft range as per Saudia website|
|**maximum_cruising_altitude_in_ft**|*int*|aircraft_configs|The aircraft max altitude as per Saudia website|
|**length_in_m**|*int*|aircraft_configs|The aircraft length as per Saudia website|
|**cruising_speed_in_kmh**|*int*|aircraft_configs|The aircraft speed as per Saudia website|
|**seating_capacity**|*string*|aircraft_configs|Total number of seats in each class as per Saudia website or 'class not offered if NA'|
|**\[class\]\_seats**|*int*|aircraft_configs|The number of seats in the class as per Saudia website or 'class not offered if NA'|
|**\[class\]\_\[width/pitch\]\_in_inches**|*float*|aircraft_configs|The width/pitch of seats in the class as per Saudia website or 'class not offered if NA'|
|**\[class\]\_abreast**|*string*|aircraft_configs|The division of seats in the class as per Saudia website or 'class not offered if NA'|
|**\[class\]\_has_\[amenity\]**|*boolean*|aircraft_configs|True if amenity offered in the class as per Saudia website|
