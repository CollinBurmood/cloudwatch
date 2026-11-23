# CloudWatch

A futuristic, responsive weather dashboard built as a static website. It uses Open-Meteo for free weather and geocoding data, and Leaflet + CARTO/OpenStreetMap tiles for the map. No paid API key is required.

## Features
- Current conditions and feels-like temperature
- Hourly forecast with precipitation probability
- 7-day forecast
- City and 5-digit ZIP search
- Browser geolocation (permission-based)
- Humidity, wind, UV index, precipitation, sunrise and sunset
- Interactive location map and hourly temperature curve
- Responsive neon/gradient visual design

## Publish with GitHub Pages
1. Sign in to GitHub as `CollinBurmood`.
2. Create a new **public** repository named `cloudwatch` (or another name you prefer).
3. Upload `index.html` to the repository root. You can also upload this README.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait a minute or two. GitHub will show your live site URL in the Pages section.

If you name the repository `CollinBurmood.github.io`, the site will publish at `https://CollinBurmood.github.io/`. Otherwise, the usual URL is `https://CollinBurmood.github.io/cloudwatch/`.

## Run locally
Open `index.html` in a browser. For best results, serve the folder with a local static server because browser geolocation requires a secure context (HTTPS or localhost).

## Data and privacy
Weather and geocoding requests go to Open-Meteo. The map loads map tiles from CARTO. Your location is only requested after you press the location button; otherwise the page starts with Oakland, Tennessee. No account or API key is needed.
