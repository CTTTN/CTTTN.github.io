## Contact

To get in touch with the network, you can contact individual <a href="members.html" class="green">members</a> or send an email via the following contact link:

<a href="mailto:ctttnetwork@gmail.com" class="green">Click here to send an email</a>

<div id="map" style="height:400px;"></div>
<script>
  var map = L.map('map').setView([47.1599,9.5540], 4);
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
  }).addTo(map);
  var pin = new Icon(iconSize: [20, 50]);
  var marker = L.marker([50.8552,4.3755], {icon: pin}).addTo(map);
  var marker = L.marker([51.0845,3.6289], {icon: pin}).addTo(map);
  var marker = L.marker([41.3925,2.1404], {icon: pin}).addTo(map);
  var marker = L.marker([53.2218,6.5648], {icon: pin}).addTo(map);
</script>
