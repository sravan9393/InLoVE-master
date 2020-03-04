# InLoVE
## Indoor Localization Using Voice Enabled Systems

### Project proposal:
https://github.com/pavankotas/InLoVE/blob/master/InLoVE.pdf

### Project Final Poster:
https://github.com/pavankotas/InLoVE/blob/master/InLoVE%20project%20poster.pdf

### Project Demo Video Link:
https://youtu.be/VWIv5Vp9P4c

### Source Code:

1) Code for ESP32 tracking device - could be either phone or key or watch
https://github.com/pavankotas/InLoVE/blob/master/Wifi%20Accesspoint%20ESP32.ino

2) Code for ESP32 Scanners which are configured as web server in Amazon EC2 - which tracks the device and populates the updated RSSI signal value.   
https://github.com/pavankotas/InLoVE/blob/master/Scanner%20ESP32%20web%20server.ino

3) Code for Amazon Lambda function - which gets the distances from 4 scanners and does triangulization to get the position of the device.
https://github.com/pavankotas/InLoVE/blob/master/alexa_skill.js
