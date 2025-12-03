gi
[style.css](https://github.com/user-attachments/files/23893697/style.css)
#map {
    height: 500px;
    width: 100%;
}[script.js](https://github.com/user-attachments/files/23893700/script.js)
document.addEventListener('DOMContentLoaded', function() {
    var map = L.map('map').setView([40.7128, -74.0060], 12);

    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);

    L.marker([40.7128, -74.0060]).addTo(map)[proyecto.html](https://github.com/user-attachments/files/23893702/proyecto.html)<!DOCTYPE html>
<html>
<head>
    <title>Mapa Lenguas Indígenas</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="map"></div>
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
    <script src="script.js"></script>
</body>
</html>


        .bindPopup('¡Este es Nueva York!')
        .openPopup();
});
