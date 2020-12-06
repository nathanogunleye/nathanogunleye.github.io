---
layout: single
title: National Train Hunter
permalink: /national-train-hunter/
excerpt: ""
header:
  overlay_image: /assets/images/nationaltrainhunter/bakerloo_line_platform.jpg
  overlay_filter: 0.5
  caption: "Elephant & Castle Bakerloo Line Platform"
  actions:
    - label: "GitHub (App)"
      url: "https://github.com/NathanO14/National-Train-Hunter-Flutter"
    - label: "GitHub (API)"
      url: "https://github.com/NathanO14/National-Train-Hunter-Web-Service"
toc: true
toc_label: "Table of Contents"
toc_icon: "align-justify"
---
National Train Hunter (NTH) 

# Background

## National Rail Enquires App

### My experience
The National Rail Enquires Android app has been a great asset to
me for a number of years. It provides a very basic and easy to use
experience for the common use case (checking train ETA times). But
since I started using the app in late 2013, it hasn't really changed.

### Changing trends
Google announced Material Design in 2014, which they implemented across
Android and their respective apps. Other apps followed, but the National
Rail app failed to follow the trend.

As I write this in late 2020, the app still looks the same as it did back
when I first downloaded it on to my Nexus 4. Over the years, as with any
mainstream app, it has seen a number of issues and bugs. Having dived into
Android development, I can tell that the developers at National Rail have
tried to support the oldest devices (probably back to Android 2.3!), but
continuing to do this only detriments the experience of users using newer
(much newer) devices.

### Other apps
I have tried using other available apps out there which have a more
modern, more material look and feel. After all, why should I try to
reinvent the wheel?

Unfortunately, none have really delivered the functionality I look
for the same way the NRE app does. So I decided to utilise my Software
Engineering skills to solve this unique issue of mine.

## Why build National Train Hunter?
The main purpose of NTH is to offer a simple and modern National Rail
train journey app with a material look and feel.

The transport enthusiast in me also wants to develop a tool to track
individual train coaches. Sadly, there is no feed available to retrieve
this type of information from National Rail (not that I know of at least).

# Early Stages
Some basic functionality has been created thus far as seen below.

## Live Trains
The app can show ETA times between two stations, and related travel warnings.

![Live Trains](assets/images/nationaltrainhunter/live_trains.gif){: style="display: block; margin-left: auto; margin-right: auto ;width: 50%" }

## Service Information
The app can also show ETA times for a particular train journey, as well as actual departure times.

![Service Information](assets/images/nationaltrainhunter/service-information.gif){: style="display: block; margin-left: auto; margin-right: auto ;width: 50%" }
