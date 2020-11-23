# Big Ideas Final Project
### Team Name: Anti-Step League
##### Group Members: 
* James Duty, jdd89@pitt.edu
* Daniel Bukowski, dab315@pitt.edu
##### Data Sets:
* Fire Incidents in Pittsbrugh: https://data.wprdc.org/dataset/fire-incidents-in-city-of-pittsburgh
  * This dataset records all fire incidents in the city of Pittsburgh since 2013, recording different aspects of the fires, most importantly, the neighborhoods in which they occurred.
* Recorded Crimes in Pittburgh: https://data.wprdc.org/datastore/dump/044f2016-1dfd-4ab0-bc1e-065da05fca2e
  * This dataset records all incidents of crime in the city of Pittsburgh since 2005. In each entry (over 225,000) a neighood is recorded, allowing the data to be analyzed on a neighborhod basis.
* Population per Neighborhood: https://data.wprdc.org/dataset/5b18c198-474c-4723-b735-cc5220ad43cc/resource/82f29015-6905-4b1c-8300-afe9bb2231b3/download/total-population.csv
  * This dataset is simply the total populations of each neighborhhod through census data, allwoing data like crime and fires to be analyzed while adjusted for population.
* Neighborhood Map Data of Pittsburgh: http://pghgis-pittsburghpa.opendata.arcgis.com/datasets/dbd133a206cc4a3aa915cb28baa60fd4_0.zip
  * This is the map data for the city of Pittsburgh, allowing us to analayze metrics geographically through GeoPandas.
* City of Pittsburgh Steps: https://data.wprdc.org/datastore/dump/43f40ca4-2211-4a12-8b4f-4d052662bb64
  * This is the amount of steps in each neighborhood of Pittsburgh, if a neighborhood did not report their steps, they were not included in the final rankings. The reasoning behind this is that if a neighborhood does not take care in reporting their steps, they should not be considered to be the best neighborhood.

#### Abstract:
Accidents and unexpected events are an unavoidable part of life that affect everybody in different ways, whether it be fires, crime, or a simple fall down the stairs. Accidents can change someone's life in an instant and therefore, are a highly important factor to consider when defining the best neighborhood. In this project, we will analyze the best neighborhood in Pittsburgh through the lens of accidents, measuring both accidents that have occurred and accidents that have the potential to occurr. Specifically, we will quantifying this by through the datasets that track crime, fire incidents, and steps.

Fire data was used to determine which neighborhood has the least fires. Crime data was used to determine where the least amount of crime is. Step data was used to determine which neighborhood has the lowest number of stairs. By combining these three metrics, we determined a safety rating for each neighborhood.

After analyzing the data, we have decided that Squirrel Hill North was the safest and therefore, best neighborhood in Pittsburgh. Windgap, North Oakland, and Squirrel Hill South closely followed.
