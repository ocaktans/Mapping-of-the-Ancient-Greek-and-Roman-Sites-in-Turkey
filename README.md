# Mapping of the Ancient Greek and Roman Sites in Turkey

### Keywords: Web Scraping, Folium

### Acknowledgements

##### Data is scraped from Wikipedia. Wikipedia has lists of the ancient Greek and Roman sites in Turkey. The link for the Roman page is [here](https://en.wikipedia.org/wiki/Category:Roman_sites_in_Turkey). First page of the Greek sites is [here](https://en.wikipedia.org/wiki/Category:Ancient_Greek_archaeological_sites_in_Turkey).

##### A vector image that was [Designed by Freepik](http://www.freepik.com) is edited to be used as custom icons. 

### The Goal of the Project

This project aims to collect spatial data for the ancient Greek and Roman sites in Turkey and visualize these sites on an interactive map. So that users can observe these sites and get additional info about them on the map via tooltips and popups. Distribution, quantity and density of these sites can be examined and routes can be set for travel plans etc.

### Contents

This repository has the necessary icons. The URLs of these icons are used in the process. 

A Jupyter notebook that displays all steps from scratch can also be found in the repository. The notebook performs web scraping with BeautifulSoup and created functions. It also creates the map and edits it with folium. Steps are explained in the notebook.

A CSV file that contains the sites with their location data can also be found here.

Finally, the map can be found as an HTML file in the "docs" folder. Rendered version of the map can be found [here](https://ocaktans.github.io/Mapping-of-the-Ancient-Greek-and-Roman-Sites-in-Turkey/themap.html).
