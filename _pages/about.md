---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a first-year Ph.D. student at the Industrial Engineering and Business Information Systems (IEBIS) group in the Behavioural, Management and Social Sciences (BMS) faculty at the [University of Twente](https://www.utwente.nl/en/). My research focuses on developing resource flow optimization models for hubs as part of the EU Horizon program ['IS2H4C'](https://is2h4c-project.eu/).

## Research Interests

My research interests revolve around **optimization** and **stochastic dynamic programming**.

Previous research experience includes:
- Vehicle scheduling problems (ILP, heuristic algorithms)
- Product popularity ranking (data analytics, machine learning)

Currently focusing on optimizing resource flows for circular hubs.

## Education

- **Ph.D. in Industrial Engineering** - University of Twente (2024-present)
- **M.S. in Management Science** - Zhejiang University (2021-2024)
- **B.S. in Transportation Engineering** - Shanghai Jiao Tong University (2017-2021)

## News

| Date | Event |
|------|-------|
| 2024.12 | Attended the [Winter School](https://www.ntnu.edu/studies/courses/I%C3%98404) on Advanced Stochastic Optimization at NTNU, Trondheim, Norway |
| 2024.06 | First conference presentation at [5th CESUST 2024](https://easychair.org/cfp/5thCESUST2024) in Chania, Greece |
| 2024.03 | Graduated from Zhejiang University with Master's degree |
| 2023.12 | Published first paper in INFORMS Journal on Applied Analytics |

## Academic Travels

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=" crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script>

<div id="academic-map" style="height: 400px; width: 100%; border-radius: 8px; margin-bottom: 20px;"></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var map = L.map('academic-map').setView([52, 10], 4);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
  }).addTo(map);

  var locations = [
    {
      coords: [52.2215, 6.8937],
      title: "Enschede, Netherlands",
      description: "University of Twente - PhD (2024-present)",
      color: "#2196F3"
    },
    {
      coords: [35.5138, 24.0180],
      title: "Chania, Greece",
      description: "5th CESUST Conference (June 2024)",
      color: "#4CAF50"
    },
    {
      coords: [63.4305, 10.3951],
      title: "Trondheim, Norway",
      description: "Winter School at NTNU (December 2024)",
      color: "#4CAF50"
    },
    {
      coords: [53.8008, -1.5491],
      title: "Leeds, UK",
      description: "Conference (June 2025)",
      color: "#FF9800"
    },
    {
      coords: [40.8475, 25.8735],
      title: "Alexandroupolis, Greece",
      description: "Conference (June 2026)",
      color: "#FF9800"
    }
  ];

  locations.forEach(function(loc) {
    var marker = L.circleMarker(loc.coords, {
      radius: 8,
      fillColor: loc.color,
      color: "#fff",
      weight: 2,
      opacity: 1,
      fillOpacity: 0.8
    }).addTo(map);

    marker.bindPopup("<b>" + loc.title + "</b><br>" + loc.description);
  });
});
</script>

<div style="font-size: 0.9em; color: #666;">
<span style="color: #2196F3;">●</span> Home institution &nbsp;
<span style="color: #4CAF50;">●</span> Past events &nbsp;
<span style="color: #FF9800;">●</span> Upcoming events
</div>

## Personal

In my spare time, I'm an avid reader and a passionate traveler. My favorite book is "Gone with the Wind" - I admire Scarlett's energy and unyielding spirit.

**2024:** Moved to the Netherlands, marking my first time living abroad. Explored seven countries: Netherlands, Germany, Greece, Austria, Czech Republic, Hungary, and Norway.

**2023:** First international adventure to Osaka, Japan. Previously explored Beijing, Shanghai, Hangzhou, Xiamen, Kunming, and Lanzhou in China.
