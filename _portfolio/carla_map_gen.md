---
title: "Automatic map and route generator from OSM data in Carla"
collection: projects
permalink: /projects/carla_map_gen
excerpt: 'An automatic map generator from OSM data for Carla.'
date: 2019-9-13
# venue: 'IEEE Robotics and Automation Letters (RA-L) (In Review)'
# paperurl: 'https://arxiv.org/abs/1909.07843'
authors: '**Rui Chen**'
image: 'auto_gen_map_pitts.png' 
video: 'https://www.youtube.com/embed/DuCVeBRDr7E'
archive_video: 'https://www.youtube.com/embed/DuCVeBRDr7E'
codeurl: 'https://github.com/ruichen-v/carla'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
OSM map data and GPS route import
============================
* I integrated a modified fork of [**StreetMapPlugin**](https://github.com/ue4plugins/StreetMap) (as submodule) to enable automatic map import and road mesh generation from OSM data.
* I implemented automatic route planner generation from GPS trajectories as **RouteGenerator**.
* The above two functionalities can be used together to easily simulate driving trajectories recorded from real-world traffic.
 
<!-- [Download paper here](https://arxiv.org/abs/1909.07843) -->
