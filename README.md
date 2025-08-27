# Effect of public toilets onto nearby Airbnb ratings in Berlin

## Description:
Visualization of corelation between the public toilet locations and the Airbnb Ratings in Berlin. Javascript + Leafjs

## Setup instructions:
1) Download all the files and folders to the device.
2) Download the datasets in the .csv format:
* Public toilets location: https://www.kaggle.com/datasets/ryanjt/berlin-public-toilets-location
* Airbnb ratings: https://www.kaggle.com/datasets/thedevastator/berlin-airbnb-ratings-how-hosts-measure-up?resource=download
3) Set the datasets in the ./data folder
4) Make sure, that the names of the files are: 
* data\berliner-toiletten-standorte.csv for Toilet Locations
* data\Airbnb_Berlin.csv for Airbnb Data.

## Project Structure:
./

    - README.md

    - index.html

    - map_buffer.html

    - data/

        - Airbnb_Berlin.csv

        - berliner-toileten-standorte.csv

    - img/

        - pin.img
        

## Launch Project:
1) Set up the local server in the convinient way for you:
    For example:
    py http.server -m 8008 (or choose other port)
2) Open the modern browser and go to localhost:8008

## How to use:
* The initial page contains a heat map of Airbnb ratings and Marker clusters for public toilet locations.
* Click on Marker to get additional information.
* Scroll to zoom in and out.
* The legend is located in the right bottom corner.
* Click on "Buffer" button to go to the buffer map view

## Data Sources:
* Public toilets location from https://www.kaggle.com/datasets/ryanjt/berlin-public-toilets-location. Licence https://creativecommons.org/licenses/by/4.0

* Berlin Airbnb Ratings from https://www.kaggle.com/datasets/thedevastator/berlin-airbnb-ratings-how-hosts-measure-up?resource=download Licence: Data files © Original Authors
