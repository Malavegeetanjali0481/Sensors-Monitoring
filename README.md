# Sensors-Monitoring
The equipped with multiple environmental sensors to collect real-time data and display it on the Android application dashboard. The sensor values are transmitted through the ESP32, allowing users to monitor  surroundings.
### Step 1: Sensor Testing
<ul>
<li>Collected all the required sensors. </li>
  <li>Connected each sensor individually to the ESP32.</li>
  <li>Tested every sensor using separate Arduino programs to ensure correct operation.</li>
</ul>
## Step 2: Sensor Integration
<ul>
<li>Connected all the sensors to the ESP32 using a breadboard. </li>
  <li>Combined the individual sensor programs into a single Arduino program.</li>
  <li>Verified that all sensors worked together without errors.</li>
</ul>
### Step 3: ThingSpeak Setup
<ul>
<li>Created a new ThingSpeak channel. </li>
  <li>Added fields for each sensor (Temperature, Humidity, Gas, Flame, and Soil Moisture).</li>
  <li>Obtained the Channel ID and Write API Key.</li>
</ul>
### Step 4: Wi-Fi and Data Upload
<ul>
<li> Connected the ESP32 to the Wi-Fi network.</li>
  <li>Configured the ESP32 to send sensor readings to the ThingSpeak channel using the API key.</li>
  <li>Confirmed that the sensor data was uploaded successfully.</li>
</ul>
## Step 5: Real-Time Monitoring
<ul>
<li> Opened the ThingSpeak dashboard.</li>
  <li>Observed the live graphs updating automatically based on the sensor readings.</li>
  <li>Verified that all sensor values were displayed correctly in real time.</li>
</ul>
## Step 6: Web Dashboard and Sensor Control
<ul>
<li>Created a web dashboard to display all the ThingSpeak sensor data in one place for easy monitoring. </li>
  <li>Integrated the live sensor values and graphs from ThingSpeak into the webpage.</li>
  <li>Added Turn ON and Turn OFF buttons to enable or disable sensor monitoring from the web interface.</li>
  <li>Verified that the dashboard updates in real time and provides a user-friendly interface for monitoring and controlling the sensors.</li>
</ul>
