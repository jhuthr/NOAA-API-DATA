# NOAA-API-DATA

## All contained materials have been written by Justin Huther

This repo contains a simple python program written in Jupyter Notebooks to scrape and organize information from NOAA.

You can explore the website and API [here](https://tidesandcurrents.noaa.gov/).  

NOAA data allows you to access local water levels, tide and current predictions, and other oceanographic and meteorological conditions.

  The web scraper pulls a list of Stations available, then sequentially checks each ports' data availability against the requested data.  
  
  The data is checked for errors, then some information about the port is logged.
