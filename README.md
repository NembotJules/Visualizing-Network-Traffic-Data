# Visualizing-Network-Traffic-Data
<img src = "0.png">
<img src = "1.png">
Network tracking using Wireshark Data, Google Maps and Python.
<p> The program use network traffic data from Wireshark (wire.pcap file), extracts source and destination IP adresses. Then generate a KML file with placemarks representing the location of the IP pairs</p>
<h3> Requirements</h3>
<p>Make sure you install: </p>
<ul>
  <li>dpkt</li>
  <li>pygeoip</li>
  <li>GeoIp database (GeoLiteCity.dat)</li>
</ul>
<h3>How to use the project</h3>
<ul>
  <li> Use Wireshark to capture your network traffic then export it as a PCAP file </li>
  <li> Change the name of the PCAP file in the code to whatever the name of your PCAP file</li>
  <li> Replace the #### by your public IP Adress</li>
  <li> Run the code</li>
  <li> Import the KML file generated in Google Maps</li>
  <li> And Voila! Thanks</li>
</ul>
