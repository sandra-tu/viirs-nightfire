# viirs-nightfire

I am not able to share the code contents of the repository containing this project due to company development reasons, but I will demo the functionality and appearance of the project here!

The Visual Infrared Imaging Radiometer Suite (VIIRS) Nightfire [dataset](https://eogdata.mines.edu/products/vnf/) consists of near-infrared and short-wave infrared data collected every night. Without sunlight interference, detected points can be fully attributed to combustion sources including wildfires, gas flares, and volcanoes. The purpose of the visualisation platform is to be able to easily query and visualise the Nightfire data by date, as well as identifying trends in areas of interest.

![Landing page of application](https://i.imgur.com/n83aAk9.png)

# Features
The control widget in the top left of the page is where the user is able to query the data and see analyses. The control widget is split into three tabs: filter, navigation, and analysis.

Under the filter tab, the user is able to filter points by temperature and radiant heat intensity ranges, as well as change the colour mapping of the data points based on different parameters. There is also an option to change the cmap used for aesthetic purposes.

### Colour map data by parameters

![Colour map data by parameters](https://i.imgur.com/u0wocFA.gif)

### Filter points by temperature and radiant heat intensity ranges

![Points being filtered by temperature and RHI range](https://i.imgur.com/hC7gNmy.gif)

Under the navigation tab, the user is able to query the data by date as well as select an area of interest to retrieve a date range.

### Query data by date
![Visualise data by date](https://i.imgur.com/EV3QnqI.gif)


