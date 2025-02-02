# Twitch Tools und Overlays

Eine kleine (bald) Sammlung nützlicher Tools und Twitchoverlays. Entweder zum selber hosten oder über [meine Webseite](https://nightbert.de).

## Wetter Overlay
![Vorschau des Wetter Overlays](https://nightbert.de/twitch/thumbnails/weather-overlay.png)

Zeigt aktuelle Wetterdaten des Orts an. Die Daten werden anhand der Geodaten des Geräts ermittelt. Also perfekt für IRL-Streams, sofern OBS auf dem mobilen Gerät läuft.<br><br>
Der Standort kann aber auch über die URL definiert werden. Die Daten werden von <a href="https://open-meteo.com/" target="_blank" rel="noopener">Open Meteo</a> & <a href="https://openstreetmap.org" target="_blank" rel="noopener">OpenStreetMap</a> zur Verfügung gestellt.

### Steuerung über URL-Parameter

- Koordinaten festlegen: `?lat=52.520008&lon=13.404954`
- Module ausblenden: `?hide=parameter` (mehrere mit & verbinden)  
Beispiel: `https://nightbert.de/twitch/weather-overlay.html?lat=52.520008&lon=13.404954&hide=geo-location`

### Verfügbare Module

- `location`: Ortsname
- `geo-location`: Koordinaten  
- `temperature`: Temperatur-Ansicht
- `weather`: Wetter-Details
- `wind`: Windanzeige

[Direkt zum Wetter Overlay](https://nightbert.de/twitch/weather-overlay.html)
