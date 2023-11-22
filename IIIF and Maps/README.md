.ve-header "IIIF and Maps"

This is a test site for working with Maps in IIIF.

# Map of Milwaukee 1835

.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/25694/manifest.json right

Map of Milwaukee as it Appeared in 1835 & 6, Made from U.S. Surveys and from Minutes, furnished by Jas. S. Buck & Dr. E. Chase / Milwaukee, Lith. & Eng. Co. ; G.B. Seaman Del. Showing lots and houses of early settlers of Milwaukee, including Dr. E. Chase and J.S. Buck. "Entered according to act of Congress in year 1876 by Jas. S. Buck with Librarian of Congress."

# Zooming in on a map image

.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/25694/manifest.json left

We can zoom in on a specific pixel location (not geographic yet!) by identifying those coordinates and then including them here. To find ==Cabbage Hollow=={3364,2793,1032,1379} in Milwaukee, for example. 

# Where is all this?

.ve-map Q37836 8 marker left

The way we are pointing to the region in this section is by using the Wikidata ID for ==Milwaukee=={Q37836}, which can be found by looking up Milwaukee in [Wikidata](https://www.wikidata.org/) . 

# How else could we show the Milwaukee region?

.ve-map  Q37836 8 marker basemaps=Esri_WorldImagery right

In this case, the only change is the basemap, which is now using the Esri World Imagery map.

# How else could we show the Milwaukee region?

.ve-map  Q37836 8 marker basemaps=OpenTopoMap left

In this case, the only change is the basemap, which is now using the OpenTopMap map.

# Full width

And here the 50% width limitation has been eliminated. [Basic map examples in Juncture](https://www.juncture-digital.org/components/map?id=basic-map-examples)

.ve-map  Q37836 8 marker basemaps=Esri_WorldImagery 

# Map layer and Wikidata

.ve-map 43.05,-87.95 8 width=50% 
    - Q1006865 layer=Cities
    - Q462161 layer=Cities
    - Q1569527 layers=Cities
    
In this example, the cities are identified simply by locating their Wikidata ID. One note - the zoom here is important. If it is too narrow, not all of the cities will appear by default. This is something you can play around with until you get it right.     

# Map with Allmaps Historic Map

.ve-map 43.05,-87.95 8
    - allmaps=8b9c456c4c9113a9
