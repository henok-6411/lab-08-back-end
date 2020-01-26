# lab-08-back-end
Number and name of feature: ________________________________

Estimate of time needed to complete: _____

Start time: _____

Finish time: _____

Actual time needed to complete: _____


# Project Name

**Author**: Cas Olejniczak, Henok Gebremedhn
**Version**: 1.2.0 (increment the patch/fix version number if you make more commits past your first submission)

## Overview
An application that allows the user to explore any city entered, providing the user with an eight-day weather forecast for the city and events within 7 miles of the city's central latitude and longitude.

## Getting Started
1. Download the application by cloning code from GitHub
2. run npm i [dependencies]
* dependencies include dotenv, express, cors, pg, and superagent

## Architecture
This is a node application which:
* Utilizes a static front-end developed by Code Fellows, 
* Utilizes JavaScript & SQL, and
* Utilizes dotenv, express, cors, postgres, and superagent.

## Change Log
01/20/2020 --- 1.0.0 --- Allows the user to access location and weather data for one location, provided in a JSON file

01/23/2020 --- 1.1.0 --- Allows the user to access location, weather, and event data for any valid location utilizing LocationIQ, Darksky, and Eventful APIs

01/25/2020 --- 1.2.0 --- Allows the same features as version 1.1.0, with added functionality to use postgres databases to cache information (for increased speed of pageload)

## Credits & Collaborators
Big thanks to Greg Dukes for Demo Code
Big thanks to Sian Culligan for leading our group programming session
Big thanks to group programming participants for all of their contributions:
* Sue Duclos
* Madison Stehle
* Daniel Nguyen
* Kory Jackson
* Krystal Madrinan
* Thomas Tilahun
* Kai Hansen