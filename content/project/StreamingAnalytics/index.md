---
title: Real-time probablistic count (Durand-Flajolet) implementation using Apache Storm
summary: Real-time analytics use case implementation for probablistic distinct count using distributed stream processing (Apache Storm).
tags:
- Stream Processing
- Distributed Computing
- Real-time Analytics
date: "2016-05-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Distinct count Apache Storm topology
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/imbesat-rizvi/Probablistic_Count_Durand-Flajolet_Implementation_using_Storm"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Distributed stream processing of meetup.com streams for probabilistic counting by [Durand-Flajolet algorithm](http://algo.inria.fr/flajolet/Publications/DuFl03.pdf) using Apache Storm. Streams of data can be processed for the purpose of distinct or unique count of field enteries which can be of interest to us. This nature of problem is referred to as “Counting distinct elements in a stream”. The data processed for the project was from meetup.com [RSVP](https://www.meetup.com/meetup_api/docs/stream/2/rsvps/) and [EVENT](https://www.meetup.com/meetup_api/docs/stream/2/open_events/) streams.