# PhilyRouteFinder

### Description
In this project, I aim to explore the question of how one can travel from point A to point B safely in Philadelphia in certain time of 
day, in other words, finding the safest route for the individual that will make the trip. The resulting dashboard will allow the users 
to type in the origin, destination, and the time of departure. The product will also provide its users with three mode options: driving, bicycling, and walking. For both driving and bicycling, the recommended route will try to avoid places with a high frequency of crashes; and when it comes to walking, it will steer clear of locations where crimes are most likely to take place.

### Required Libraries
- `numpy`
- `pandas`
- `geopandas`
- `base64`
- `datetime`
- `osmnx`
- `networkx`
- `shapely`
- `geopy`
- `folium`
- `pyrestcli`
- `carto`
- `altair`
- `holoviews`
- `geoviews`
- `param`
- `panel`

### Result
From the above repo, you will find [demo.ipynb](https://github.com/makwingchi/PhillyRouteFinder/blob/master/demo.ipynb), in which I describe the complete workflow I employ to create this project, including the introduction of the project, the explanation of each technical step, and the result; [app.ipynb](https://github.com/makwingchi/PhillyRouteFinder/blob/master/app.ipynb), where a dashboard can be produced by running the code inside the jupyter notebook.
