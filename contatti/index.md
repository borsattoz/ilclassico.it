---
layout: default
title: "Contatti"
menu: true
order: 5
permalink: ':path/'
custom_css:
- 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.css'
custom_js:
- 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.js'
---

# Contatti e orari
<style scoped>
#map { height: 180px; }
</style>
<div id="map"></div>

<script>
var map = L.map('map').setView([51.505, -0.09], 13);

L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);

var marker = L.marker([51.5, -0.09]).addTo(map);
</script>
