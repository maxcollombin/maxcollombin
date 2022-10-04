### Hi there 👋

- My name is Maxime Collombin
- I'm a geospatial web specialist working currently at the [University of Applied Sciences of Western Switzerland (HEIG-VD)](https://heig-vd.ch/rad/instituts/mei/mediamaps).

- I'm a geologist by training and hold a Master of Science in Geology from the [University of Lausanne, Switzerland](https://www.unil.ch/gse/fr/home.html).

- My areas of interest are:
    - ecology and the environment
    - the web and new technologies
    - geographic information systems (GIS)
    - open source technologies
    - the representation of cartographic information 
---

### ⚒ Languages and Tools :

<div>
    <a href="https://qgis.org/en/site/"><img src="https://github.com/qgis/QGIS/blob/master/images/icons/qgis-icon-60x60.png" title="QGIS" alt="QGIS" width="40" height="40"/></a>&nbsp;
    <a href="https://pro.arcgis.com/en"><img src="https://www.esri.com/content/dam/esrisites/en-us/common/icons/product-logos/ArcGIS-Pro.png" title="ArcGIS Pro" alt="ArcGIS Pro" width="40" height="40"/></a>&nbsp;
    <a href="https://enterprise.arcgis.com/en/"><img src="https://www.esri.com/content/dam/esrisites/en-us/common/icons/product-logos/ArcGIS-Enterprise.png"  title="ArcGIS Enterprise" alt="ArcGIS Enterprise" width="40" height="40"/></a>&nbsp;
    <a href="https://geoserver.org/"><img src="https://avatars.githubusercontent.com/u/186522?s=280&v=4" title="GeoServer" alt="GeoServer" width="40" height="40"/></a>&nbsp;
    <a href="https://openlayers.org/"><img src="https://openlayers.org/assets/theme/img/logo70.png" title="OpenLayers" alt="OpenLayers" width="40" height="40"/></a>&nbsp;
    <a href="https://leafletjs.com/"><img src="https://github.com/maxcollombin/maxcollombin/blob/main/assets/leaflet.png" title="Leaflet" alt="Leaflet" width="40" height="40"/></a>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
    <a href="https://www.python.org/"><img src="https://github.com/devicons/devicon/blob/master/icons/python/python-plain-wordmark.svg" title="Python" alt="Python" width="40" height="40"/></a>&nbsp;
    <a href="https://www.postgresql.org/"><img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-plain-wordmark.svg" title="PostgreSQL" **alt="PostgreSQL" width="40" height="40"/></a>&nbsp;
    <a href="https://www.docker.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain-wordmark.svg" title="Docker" **alt="Docker" width="40" height="40"/></a>&nbsp;
    <a href="https://github.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="GitHub" **alt="GitHub" width="40" height="40"/></a>&nbsp;
</div>

---

### 🔥 My Stats :

---

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=maxcollombin&theme=dark&background=000000)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=maxcollombin&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

---

### ✉ How to reach me:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/maxime-collombin-995268136/)](https://www.linkedin.com/in/maxime-collombin-995268136/)
[![Contact](https://img.shields.io/badge/Contact-vCard-lightgrey&?style=for-the-badge&https://contacts.heig-vd.ch/mcn)](https://contacts.heig-vd.ch/mcn)

<!DOCTYPE html>
<html>
    <head>
        <title>Haus der Kantone</title>
        <link rel="stylesheet" href="http://cdn.leafletjs.com/leaflet-0.6.4/leaflet.css" />
        <script src="http://cdn.leafletjs.com/leaflet-0.6.4/leaflet.js"></script>
        <script type="text/javascript" src="http://code.jquery.com/jquery-1.7.1.min.js"></script>
    </head>
    <body>
        <div id="map" style="width: 600px; height: 400px;"></div>
        <script>
            var map = L.map("map").setView([46.8, 8.2], 8);
            L.tileLayer("http://{s}.tile.osm.org/{z}/{x}/{y}.png", {
                attribution:
                    'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, ' + '<a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' + 'Imagery © <a href="http://mapbox.com">Mapbox</a>',
                maxZoom: 18,
            }).addTo(map);
            var marker = L.marker([46.95074, 7.44217]).addTo(map);
            marker.bindPopup("<b>Haus der Kantone</b><br>Speichergasse 6<br>3011 Bern").openPopup();
        </script>
    </body>
</html>





