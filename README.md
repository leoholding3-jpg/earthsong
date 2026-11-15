# EarthSong: Listening to Earth

EarthSong is a web application that combines visualization and sonification of NASA Earth observation data. Users select a region (starting with Angola, then the rest of Africa) and a time period, and see the same thermal detections on a map and hear them as a synchronized soundscape.

## Data sources

- NASA FIRMS (Fire Information for Resource Management System): https://firms.modaps.eosdis.nasa.gov/
- NASA GIBS (Global Imagery Browse Services): https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal/gibs-api

## Planned architecture

- Interface: React + Vite, Leaflet map
- Data processing: Python + FastAPI
- Sound: Web Audio API

## Current status

Design and architecture proposal. Real FIRMS data loading and the sound engine are the next development steps. A thermal detection is not the same as a confirmed fire; the app presents data as thermal activity detections.

## Use of AI tools

AI assistance was used for brainstorming, documentation writing and translation. No AI-generated images, video or audio are included.
