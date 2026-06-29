# Sensors-Monitoring
The equipped with multiple environmental sensors to collect real-time data and display it on the Android application dashboard. The sensor values are transmitted through the ESP32, allowing users to monitor  surroundings.
## Step 1: Sensor Testing
Collected all the required sensors.
Connected each sensor individually to the ESP32.
Tested every sensor using separate Arduino programs to ensure correct operation.
## Step 2: Sensor Integration
Connected all the sensors to the ESP32 using a breadboard.
Combined the individual sensor programs into a single Arduino program.
Verified that all sensors worked together without errors.
## Step 3: ThingSpeak Setup
Created a new ThingSpeak channel.
Added fields for each sensor (Temperature, Humidity, Gas, Flame, and Soil Moisture).
Obtained the Channel ID and Write API Key.
## Step 4: Wi-Fi and Data Upload
Connected the ESP32 to the Wi-Fi network.
Configured the ESP32 to send sensor readings to the ThingSpeak channel using the API key.
Confirmed that the sensor data was uploaded successfully.
## Step 5: Real-Time Monitoring
Opened the ThingSpeak dashboard.
Observed the live graphs updating automatically based on the sensor readings.
Verified that all sensor values were displayed correctly in real time.
## Step 6: Web Dashboard and Sensor Control
Created a web dashboard to display all the ThingSpeak sensor data in one place for easy monitoring.
Integrated the live sensor values and graphs from ThingSpeak into the webpage.
Added Turn ON and Turn OFF buttons to enable or disable sensor monitoring from the web interface.
Verified that the dashboard updates in real time and provides a user-friendly interface for monitoring and controlling the sensors.
