# INM433 - Visual Analytics Courseworks
Two small visual analytics projects

1. SwissPopularInitiative contains the report on "Factors Explaining the Spatial Variations in the Results of the Swiss Popular Initiative 'Against Mass Immigration' " and the source-code written in R. It uses [tmap ](https://cran.r-project.org/web/packages/tmap/index.html) for geographical plotting and [spgwr](https://cran.r-project.org/web/packages/spgwr/index.html) for computing geographically weighted regressions.
![gwr](SwissPopularInitiative/InteractiveMap.gif)

2. Origin-Destination Map for TFL Oyster card journeys in London during November 2009 (5% sample). The Tableau sheet allows for time and travel-product filtering. OD-Maps are "maps in maps" that divide the geographical space into a 2-dimensional grid that has the same number of grid cells for both the nested maps and the base map. More information on OD-Maps can be found in the original paper by [Wood et al.](http://openaccess.city.ac.uk/537/1/wood_visualization_2010.pdf). The TFL data was obtained from the [London Datastore](https://data.london.gov.uk/dataset/oyster-card-journey-information)
![odmap](TFLOriginDestinationMap/ODMap.gif)
