# leaflet-challenge

# Part 1: Create the Earthquake Visualization

![Alt text](Images/2-BasicMap.png)

Your first task is to visualize an earthquake dataset. Complete the following steps:

# 1. Get your dataset. To do so, follow these steps:

  1. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. 
     The following image is an example screenshot of what appears when you visit this link:

     ![Alt text](Images/3-Data.png)

  2. When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. 
     The following image is a sampling of earthquake data in JSON format:

     ![Alt text](Images/4-JSON.png)


# 2. Import and visualize the data by doing the following:
  
  1. Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
  2. Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater 
     depth should appear darker in color.
  3. Include popups that provide additional information about the earthquake when its associated marker is clicked.
  4. Create a legend that will provide context for your map data.
  5. Your visualization should look something like the preceding map.

  ## Output:
  ![Alt text](Images/Base_Map.png)
