---
title: District 1
location: 
  # center: [4.4665974,51.9274653]
  zoom: 15
warpedMaps:
  - url: assets/annotations/rotterdam-base-map.json
    caption: Rotterdam Highrise Zone (2019)
    useBounds: true
    # options:
      # saturation: 0
      # colorize: true
      # colorizeColor: "#39648d"
      # removeColor: true
      # removeColorColor: "#FFFFFF"
  - url: https://annotations.allmaps.org/manifests/7737cec074ed3ecf
    caption: Map of Rotterdam
    provenance: Rotterdam Municipal Works
    homepage: https://hdl.handle.net/11245/3.39844
    options:
      saturation: 0
layers:
  - layer: high-rise-vision-fill
    visibility: visible
  - layer: high-rise-vision-line
    visibility: visible
  - layer: sunspots-high-rise-2019-fill
    visibility: none
  - layer: sunspots-high-rise-2019-line
    visibility: visible
subslideshows:
  - district-1
---

The pink outline marks the part of the image we want to place on a map.
This **mask** will hide the paper outside that area. For now, the full image
stays visible so you can see the boundary.
