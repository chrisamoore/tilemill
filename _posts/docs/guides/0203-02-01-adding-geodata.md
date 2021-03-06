---
layout: book
section: documentation
category: TileMill
tag: Guides
title: "Adding MapBox Geodata"
permalink: /docs/guides/add-geodata
prereq:
- "[Installed](/tilemill/docs/install) TileMill on your computer."
nextup:
- "[Using conditional styles](/tilemill/docs/crashcourse/conditional-styles/) to control the appearance of points based on data."
- "[Adding tooltips](/tilemill/docs/crashcourse/tooltips/) to your map."
- "[Adding a legend](/tilemill/docs/crashcourse/legends/) to your map."
- "[Exporting](/tilemill/docs/crashcourse/exporting/) your map."
---

{% include prereq.html %}

The MapBox GeoData Library is a collection of free datasets that have been optimized to work well with TileMill and offer an excellent source for geographic data. For more details about the MapBox GeoData Library, see our [technical reference](/tilemill/docs/manual/mapbox-geodata). 

For practice, we'll add a layer of populated places around the world.

1. Click **Add layer**.
![Add Layer](/tilemill/assets/pages/geodata-1.png)
2. Enter `cities` in the **ID** field. You'll use this ID to reference this layer.  
3. For the **Datasource** field, click **Browse** to navigate to the MapBox GeoData library.  
4. Click the **MapBox** button to navigate to the library.  
![Navigate](/tilemill/assets/pages/geodata-4.png)
5. Select the geodata file you would like to add to your project. Here we will navigate to `natural-earth-1.4.0` - `cultural/` - `10m-populated-places-simple.zip`.  
![Select](/tilemill/assets/pages/geodata-5.png)
6. Click **Done** to confirm your selection.  
7. Click the **Save & Style** button to add the layer to your project and insert a default Carto rule for the layer.  
![Save and Style](/tilemill/assets/pages/geodata-7.png)
8. Preview the result in the map preview pane.  
![Preview](/tilemill/assets/pages/geodata-8.png)  

{% include nextup.html %}