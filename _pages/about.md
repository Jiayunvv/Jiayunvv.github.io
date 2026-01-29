---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div style="background-color:rgb(216, 227, 153); color: Black; padding: 10px; border-radius: 5px;">
  😁 Hey! Welcome to my academic page!
</div>


I'm currently a first-year Ph.D. student at the Industrial Engineering and Business Information Systems (IEBIS) group in the Behavioural, Management and Social Sciences (BMS) faculty at the [University of Twente (UT)](https://www.utwente.nl/en/). My research focuses on developing resource flow optimization models for hubs as part of the EU Horizon program ['IS2H4C'](https://is2h4c-project.eu/).

In my spare time, I'm an avid reader and a passionate traveler. My favorite book is "Gone with the Wind" because I admire Scarlett's energy and her unyielding spirit.

### Research Interests

My research interests revolve around optimization.
My previous research experience included vehicle scheduling problems (ILP, heuristic algorithm) and product popularity ranking (data analytics, indicators, machine learning).

I am now focusing on stochastic dynamic programming, with an focus on optimizing resource flows for circular hubs.


### Education Background
I hold a Bachelor's degree in Transportation from Shanghai Jiao Tong University, China (QS ranking 51), and a Master's degree in Management Science from Zhejiang University, China (QS ranking 44).


### Experiencing the World

[Wrote in 2024.12: ] I realized a part of my dream this year! In 2024, I moved to the Netherlands, marking my first time living in a foreign country. I explored seven countries, including Netherlands, Germany, Greece, Austria, the Czech Republic, Hungary, and Norway. The world is vast, and I'm eager to see and experience even more!

[Wrote in 2023.11: ]
When it comes to traveling, I've explored several famous cities in China, including Beijing, Shanghai, Hangzhou, Xiamen, Kunming, and Lanzhou. In summer of 2023, I embarked on my first international adventure to Osaka, Japan, which left a lasting impression on me with its unique culture and breathtaking landscapes. I'm eager to continue expanding my horizons and experiencing the wonders of the world.


### Academic Travels in Europe 🌍

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" crossorigin=""></script>

<div id="map" style="height: 420px; width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.15); margin: 15px 0;"></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var map = L.map('map', {
    zoomControl: true,
    scrollWheelZoom: false
  }).setView([52, 12], 4);

  L.tileLayer('https://{s}.basemaps.cartocdn.com/rastertiles/voyager/{z}/{x}/{y}{r}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> &copy; <a href="https://carto.com/">CARTO</a>',
    maxZoom: 19
  }).addTo(map);

  var homeIcon = L.divIcon({
    html: '<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); width: 32px; height: 32px; border-radius: 50%; border: 3px solid white; box-shadow: 0 3px 10px rgba(0,0,0,0.3); display: flex; align-items: center; justify-content: center;"><span style="color: white; font-size: 16px;">🏠</span></div>',
    className: '',
    iconSize: [32, 32],
    iconAnchor: [16, 16]
  });

  var pastIcon = L.divIcon({
    html: '<div style="background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); width: 28px; height: 28px; border-radius: 50%; border: 3px solid white; box-shadow: 0 3px 10px rgba(0,0,0,0.3); display: flex; align-items: center; justify-content: center;"><span style="color: white; font-size: 14px;">✓</span></div>',
    className: '',
    iconSize: [28, 28],
    iconAnchor: [14, 14]
  });

  var futureIcon = L.divIcon({
    html: '<div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); width: 28px; height: 28px; border-radius: 50%; border: 3px solid white; box-shadow: 0 3px 10px rgba(0,0,0,0.3); display: flex; align-items: center; justify-content: center;"><span style="color: white; font-size: 14px;">★</span></div>',
    className: '',
    iconSize: [28, 28],
    iconAnchor: [14, 14]
  });

  var locations = [
    { coords: [52.2215, 6.8937], title: "🏠 Enschede, Netherlands", desc: "University of Twente<br><i>PhD Student (2024-present)</i>", icon: homeIcon },
    { coords: [35.5138, 24.0180], title: "🇬🇷 Chania, Greece", desc: "5th CESUST Conference<br><i>June 2024</i>", icon: pastIcon },
    { coords: [63.4305, 10.3951], title: "🇳🇴 Trondheim, Norway", desc: "Winter School at NTNU<br><i>December 2024</i>", icon: pastIcon },
    { coords: [53.8008, -1.5491], title: "🇬🇧 Leeds, UK", desc: "Conference<br><i>June 2025</i>", icon: futureIcon },
    { coords: [40.8475, 25.8735], title: "🇬🇷 Alexandroupolis, Greece", desc: "Conference<br><i>June 2026</i>", icon: futureIcon }
  ];

  locations.forEach(function(loc) {
    L.marker(loc.coords, {icon: loc.icon})
      .addTo(map)
      .bindPopup('<div style="text-align:center; min-width: 150px;"><b style="font-size: 14px;">' + loc.title + '</b><br><span style="color: #666;">' + loc.desc + '</span></div>');
  });
});
</script>

<div style="display: flex; justify-content: center; gap: 25px; margin-top: 10px; font-size: 14px; flex-wrap: wrap;">
  <span><span style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 3px 10px; border-radius: 12px; color: white; font-size: 12px;">🏠</span> Home</span>
  <span><span style="background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); padding: 3px 10px; border-radius: 12px; color: white; font-size: 12px;">✓</span> Visited</span>
  <span><span style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); padding: 3px 10px; border-radius: 12px; color: white; font-size: 12px;">★</span> Upcoming</span>
</div>


### News
- **2024.12**: 🙇‍♀️ Jiayun attended the [Winter School](https://www.ntnu.edu/studies/courses/I%C3%988404) on Advanced Stochastic Optimization at NTNU, Trondheim, Norway.
- **2024.06**: 💪 Jiayun presented for the first time at a conference, the Chania Symposium on Circular Economy and Sustainability 2024 ([5th CESUST 2024](https://easychair.org/cfp/5thCESUST2024)) in Chania,Greece.
- **2024.03**: 🎉🎉🎉 Jiayun successfully graduated from Zhejiang University and is now Ms. Wang. :)
- **2023.12**: 🤩 Jiayun published her first paper, *"Identifying Popular Products at an Early Stage of Sales Season for the Apparel Industry."* Congratulations to her!
