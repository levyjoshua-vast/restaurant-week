restaurant-week
===============

Map daytime restaurant-week participants near the Vast office

```html
<head>
   <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
   <link rel="stylesheet" href="http://cdn.leafletjs.com/leaflet-0.7.2/leaflet.css" />
   <script src="http://cdn.leafletjs.com/leaflet-0.7.2/leaflet.js"></script>

   
   
   
   


   <style>

      #map {
        position:absolute;
        top:0;
        bottom:0;
        right:0;
        left:0;
      }

   </style>
</head>

<body>

   <div class="folium-map" id="folium_a5c66ad733b147a48218188f957a8d65" style="width: 960px; height: 500px"></div>

   <script>

      

      var map = L.map('folium_a5c66ad733b147a48218188f957a8d65').setView([30.2680523673, -97.7430834286], 16);

      L.tileLayer('http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
          maxZoom: 18,
          attribution: 'Map data (c) <a href="http://openstreetmap.org">OpenStreetMap</a> contributors'
      }).addTo(map);

      
      var circle_1 = L.circle([30.2680523673, -97.7430834286], 16, {
                            color: 'black',
                            fillColor: 'blue',
                            fillOpacity: 0.6
                            });
      circle_1.bindPopup("Vast");
      map.addLayer(circle_1)
      
      var marker_1 = L.marker([30.2701089387755, -97.7497529591837]);
      marker_1.bindPopup("<b>Benji&#8217;s Cantina</b>: 716 W. 6th St. Austin, TX 78703");
      map.addLayer(marker_1)
      
      var marker_2 = L.marker([30.272885, -97.757208]);
      marker_2.bindPopup("<b>Cafe Josie</b>: 1200 B West 6th St");
      map.addLayer(marker_2)
      
      var marker_3 = L.marker([30.2632393265306, -97.7443470816327]);
      marker_3.bindPopup("<b>Chavez</b>: 111 East Cesar Chavez Austin, Texas 78701");
      map.addLayer(marker_3)
      
      var marker_4 = L.marker([30.401988, -97.727828]);
      marker_4.bindPopup("<b>Copper Restaurant & Dessert Lounge</b>: 3401 Esperanza Crossing Suite #104");
      map.addLayer(marker_4)
      
      var marker_5 = L.marker([30.263587122449, -97.7412976530612]);
      marker_5.bindPopup("<b>CRAVE</b>: 340 E 2nd Street ");
      map.addLayer(marker_5)
      
      var marker_6 = L.marker([30.2680872040816, -97.7425813877551]);
      marker_6.bindPopup("<b>Due Forni</b>: 106 E. 6th St. Suite 106 Austin, TX 78701");
      map.addLayer(marker_6)
      
      var marker_7 = L.marker([30.3191478823529, -97.739360882353]);
      marker_7.bindPopup("<b>Gusto Italian Kitchen + Wine Bar</b>: 4800 Burnet Road");
      map.addLayer(marker_7)
      
      var marker_8 = L.marker([30.264943, -97.738945]);
      marker_8.bindPopup("<b>Liberty Tavern</b>: 500 E 4th St, Austin, TX 78701");
      map.addLayer(marker_8)
      
      var marker_9 = L.marker([30.2654505106383, -97.7438875106383]);
      marker_9.bindPopup("<b>Manuel&#8217;s</b>: 310 Congress Avenue, Austin, Texas, 78701");
      map.addLayer(marker_9)
      
      var marker_10 = L.marker([30.3966884, -97.7493512704584]);
      marker_10.bindPopup("<b>Manuel&#8217;s Great Hills</b>: 10201 Jollyville Road, Austin, TX 78759");
      map.addLayer(marker_10)
      
      var marker_11 = L.marker([30.269057, -97.742337]);
      marker_11.bindPopup("<b>Roaring Fork Downtown</b>: 701 Congress Avenue, Austin, TX 78701");
      map.addLayer(marker_11)
      
      var marker_12 = L.marker([30.3886963, -97.7387067]);
      marker_12.bindPopup("<b>Roaring Fork Stonelake &#8211; North Austin</b>: 10850 Stonelake Blvd., Austin, TX 78759");
      map.addLayer(marker_12)
      
      var marker_13 = L.marker([30.2663061020408, -97.7405808163265]);
      marker_13.bindPopup("<b>Russian House Nazdorovye</b>: 307 E 5th street");
      map.addLayer(marker_13)
      
      var marker_14 = L.marker([30.2667572857143, -97.7446408571429]);
      marker_14.bindPopup("<b>Searsucker</b>: 415 Colorado St");
      map.addLayer(marker_14)
      
      var marker_15 = L.marker([30.2654548571429, -97.7436858571429]);
      marker_15.bindPopup("<b>Swift&#8217;s Attic</b>: 315 Congress Avenue");
      map.addLayer(marker_15)
      
      var marker_16 = L.marker([30.26574, -97.746472]);
      marker_16.bindPopup("<b>TRACE</b>: 200 Lavaca St.");
      map.addLayer(marker_16)
      
      var marker_17 = L.marker([30.4051642, -97.722275]);
      marker_17.bindPopup("<b>Urban an American Grill</b>: 11301 Domain Dr");
      map.addLayer(marker_17)
      
      var marker_18 = L.marker([30.266303, -97.743363]);
      marker_18.bindPopup("<b>Willie G&#8217;s Seafood and Steaks</b>: 401 Congress Ave Austin, TX 78701");
      map.addLayer(marker_18)
      
      var marker_19 = L.marker([30.2674203877551, -97.7493563469388]);
      marker_19.bindPopup("<b>Mulberry</b>: 360 Nueces #20");
      map.addLayer(marker_19)
      
      var marker_20 = L.marker([30.2704404, -97.7511482]);
      marker_20.bindPopup("<b>Tapasitas</b>: 800 West 6th street, Austin, Texas, 78701");
      map.addLayer(marker_20)
      
      var marker_21 = L.marker([30.2734720178571, -97.7592835535714]);
      marker_21.bindPopup("<b>Winflo Osteria</b>: 1315 W 6th St, Austin, TX 78703");
      map.addLayer(marker_21)
      

      

      

      

   </script>

</body>
```
