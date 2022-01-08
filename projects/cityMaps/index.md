---
date: "2022-01-08T20:00:00Z"
external_link: ""
image:
  caption: Map of Berlin
  focal_point: Center
links:
- icon: github
  icon_pack: fab
  name: Gist Code
  url: https://gist.github.com/jadenecke/5252609ef06f1655f42d8cdcd8b0b51e
slides: example
summary: R Script to download and plot OpenStreetMap data
tags:
- Maps
- OSM
title: City Maps
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

A script I wrote to generate artistic city maps from OpenStreeMap. The script downloads the data to disk and reloads it to memory, to finally create the plot. The script automatically adjusts (roughly, according to the 1° lat = 111,111m [rule](https://gis.stackexchange.com/questions/2951/algorithm-for-offsetting-a-latitude-longitude-by-some-amount-of-meters)) the coordinates to your aspect ratio in order to avoid distortions of the map. I did not manage to remove the white space on the top and right side of the plot. In addition, the code developed from a specific city to general, so there are many inherited inconveniences, especially in terms of size scaling. 

[Download the script here](https://gist.github.com/jadenecke/5252609ef06f1655f42d8cdcd8b0b51e)