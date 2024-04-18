# azure-and-rpi-based-hygrometer

The temperature has an impact on almost all the activities surrounding us. A precise determination of temperature and more importantly relative humidity is a vital factor in countless industries and different fields of science. Temperature monitoring is a key element of industrial production processes. Alloy melting in the automotive industry, the food industry, foil thermoforming in the plastic industry, or glass syringe production in the life science industry.

In this project a hygrometer is connected to Azure IoT Central using Raspberry Pi so we can see its telemetry in a real-time dashboard or python shell. A hygrometer is a device that measures both humidity and temperature. It’s good for monitoring attics, crawlspaces and other hard-to-reach locations. The proposed method aims at continuously monitoring the real time temperature and relative humidity in a cost effective way by polling sensor at fixed interval of time. Here the monitoring node is Raspberry Pi 4. The Sensor utilized is DHT11 Temperature/Humidity Sensor. The sensor is connected to the raspberry pi kit using jumper wire. The Azure IoT Hub can be used to store and display the real time temperature and relative humidity. A simple Python script is used for reading the sensor and dumping its telemetry to the screen. The temperature is displayed in degree celsius or Fahrenheit as required. To know the current temperature and relative humidity at remote location, the user can view it through the IoT Hub. Raspberry pi processed data will be updated continuously on the hub & the user will get to know the stored data on hourly and daily basis. Wireless wifi is attached so that it fetches data with the help of internet and user can access or control temperature and humidity from any part of the world.

Components used: 
a. Raspberry Pi 4B 
b. DHT 11 Temperature and humidity sensor 
c. Jumper Wires 
d. Power cable 
e. Azure IoT hub 
f. Coding language - Python
