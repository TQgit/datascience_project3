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