---
layout: single
title: London Bus Hunter
permalink: /london-bus-hunter/
excerpt: "Putting the 'fan' in bus fanatic"
header:
  overlay_image: /assets/images/londonbushunter/SN12ABU.jpg
  overlay_filter: 0.5
  caption: "9531 SN12ABU, Route C2, Abellio London"
  actions:
    - label: "Google Play"
      url: "https://play.google.com/store/apps/details?id=com.nathanodong.london_bus_hunter"
toc: true
toc_label: "Table of Contents"
toc_icon: "align-justify"
gallery:
  - url: assets/images/londonbushunter/vehicle_location.jpg
    image_path: assets/images/londonbushunter/vehicle_location.jpg
    alt: "Vehicle Location"
    title: "Vehicle Location"
  - url: assets/images/londonbushunter/vehicle_history.jpg
    image_path: assets/images/londonbushunter/vehicle_history.jpg
    alt: "Vehicle History"
    title: "Vehicle History"
  - url: assets/images/londonbushunter/route_history.jpg
    image_path: assets/images/londonbushunter/route_history.jpg
    alt: "Route History"
    title: "Route History"
  - url: assets/images/londonbushunter/rare_vehicles.jpg
    image_path: assets/images/londonbushunter/rare_vehicles.jpg
    alt: "Rare Vehicles"
    title: "Rare Vehicles"
  - url: assets/images/londonbushunter/rare_vehicles.gif
    image_path: assets/images/londonbushunter/rare_vehicles.gif
    alt: "Rare Vehicles GIF"
    title: "Rare Vehicles"
  - url: assets/images/londonbushunter/vehicle_history.gif
    image_path: assets/images/londonbushunter/vehicle_history.gif
    alt: "Vehicle History GIF"
    title: "Vehicle History"
---
London Bus Hunter (LBH) is not your typical bus ETA app. LBH unlocks
enthusiast-centric features in the palm of your hands.

# Background

## Why did I build the app?
As an avid bus enthusiast I love knowing which bus type will be
aiding me in my journeys. The official TfL website was basic
enough for me to use for retriving ETA times and bus stops (local
or by route, per direction). But gave no information on the vehicle
registration, fleet code, or operator.

I came across another website which provided the enthusiast centric
features I was looking for, but it lacked some functionality that the
average user would need. It also not very optimized for mobile,
which made it tedious to use when leisurely travelling out and about.

For a long time I had to use the TfL website and the enthusiast tool.
Instead of constantly switching tabs in my browser and struggling
to navigate desktop-focused websites, I decided to marry the two.

## Technologies

### App
Back in my university days, Java was my main tool. This made native
Android app development much easier to learn. In early 2020 I discovered
Flutter, an easy to learn framework for Android *and* iOS development!

So I took time to learn the framework and release a newer, fresher
version of the app. Easier to maintain and potential for more platform
availability

### API
The back-end was initially written in PHP. This eventually got too
difficult to maintain so I migrated to Java using Spring. This
conventiently lined up with the Java code I had for the Android app.

The Java application hosts a REST API to handle all communication
to the TfL API feed.

# Features
## Rare Vehicles
LBH will show you which vehicles are rare or new to a route. You can sort
these results by Fleet Code, Operator Name, Route Name, or ETA.

![Rare Vehicles](assets/images/londonbushunter/rare_vehicles.gif){: style="display: block; margin-left: auto; margin-right: auto ;width: 50%" }

## Route and Vehicle History
LBH stores up to 3 months worth of historical bus workings in it's database 
(Sorting functionality coming later). Historical vehicle usage data is not
provided by TfL. All data is recorded by LBH.

![Vehicle History](assets/images/londonbushunter/vehicle_history.gif){: style="display: block; margin-left: auto; margin-right: auto ;width: 50%" }

# Gallery
{% include gallery id="gallery" caption="Gallery" %}