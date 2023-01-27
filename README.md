<p align='center'>
<img src="images\yelphellp.png" width="128"/>
</p>

# YelpHelp
A simple scraping tool for Yelp.

## Version 1.0.0
Current as of 01/27/2023

## Use

```python
import os
import sys

file_dir = os.path.dirname(r'..\yelphelp.py')
sys.path.append(file_dir)
from yelphelp import YelpHelp

scraper=YelpHelp()

dataframe=scraper.scrape_data(url='<startingurl>')

```