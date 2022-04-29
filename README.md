# Repo Information
This repo contains files and folders related to data collection for the dashboard [Hold my Beer: Global Craft Breweries](https://public.tableau.com/app/profile/alice.leach/viz/HoldmyBeerGlobalCraftBreweries/HoldmyBeerCraftBreweriesoftheUnitesStates). 

Data was scraped from [BrewBound](https://brewbound.com/breweries/) in April 2022.

Project was inspired by [Kaggle Craft Beers](https://www.kaggle.com/datasets/nickhould/craft-cans) dataset by Jean-Nicholas Hould.

The repo contains the following files:
* brewbound.ipynb - script to scrape beer and brewery 
* beers_breweries2022.xlsx - data scraped from BrewBound
* Files and folders associated with poetry package management

Data quality notes:
* Beer information is only available for 25% of breweries listed
* Location data is associated with beer url so is missing - work around for this uses geopy package to reverse geocode state and country

Resources:
* [BrewBound](https://brewbound.com)
* [Poetry](https://python-poetry.org/docs/)
* [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/)
* [geopy](https://geopy.readthedocs.io/en/stable/)