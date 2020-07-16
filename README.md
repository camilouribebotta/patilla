<param ve-config
       title="Patilla"
       banner="https://upload.wikimedia.org/wikipedia/commons/a/a4/Albert_Eckhout_1610-1666_Brazilian_fruits.jpg"
       layout="vtl"
       num-maps="x"
       num-specimens="x"
       num-images="x"
       num-primary-sources="x"
       author="Camilo Uribe Botta">

<param title="Watermelon" eid="Q17507129">
<param title="Citrullus lanatus" eid="Q17507129" aliases="Anguria">
<param title="Dumbarton Oaks" eid="Q1264942">

## Watermelon

Watermelons come from Africa.
<param ve-image
title="Watermelon _Citrullus lanatus_" url="https://upload.wikimedia.org/wikipedia/commons/4/47/Taiwan_2009_Tainan_City_Organic_Farm_Watermelon_FRD_7962.jpg"
       fit="cover"
       attribution="Wikimedia Commons">

Code to add a location with a custom marker on a mapor every paragraph in this section.
<param title="Africa" eid="Q15" fill="#FF0000" marker-symbol="landmark">

Below is the code for adding a map. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. .
<param ve-map center="Q15" zoom="2" basemap="Esri_WorldPhysical">

Below is the code for adding a map with premade Geojson overlays. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. 
<param ve-map prefer-geojson center="Q15" zoom="2" basemap="Esri_WorldPhysical">
<param title="Ethiopia" eid="Q115">
<param title="Sudan" eid="Q1049">

Below is the code for adding an IIIF annotated image created through Storiiies. 
<param ve-storiiies id="8f1e1">

The code below is an example of how to add a custom geojson overlay. 
<param ve-map center="41.651031, -83.541939" zoom="6">
<param ve-map-layer geojson url="geojson/great-lakes-fruit-belt.json" title="Great Lakes Fruit Belt" fill="#FF0000" marker-symbol="landmark" active>

## Subtitle

The code below is an example of how to add a video from Youtube. 
<param ve-video id="jk0ic0D0MRo" title="Hanami">

Code for adding a Mapwarper overlay.
<param ve-map center="38.88,-77.03" zoom="14">
<param ve-map-layer mapwarper title="Cherry festival map" mapwarper-id="37798" active>

Code to add a specimen from Global Plants.
<param ve-plant-specimen eid="Q12844029" max="1" reverse="true">
