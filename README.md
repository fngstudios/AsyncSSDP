# AsyncSSDP


##This is a work in progress, could be implemented in a better way  

ESP8266 SSDP library for asyncTCP. This library generates description.xml in SPIFFS so the asyncWebServer can serve directly the file.
The old library needed a Wifiserver client object to be passed as an argument to SPD.setschema and thus didnt worked with AsyncWebserver.
All functions remain the same, but it will search for the file in SPIFFS and create if it doesnt exist.

Based on: https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266SSDP/examples/SSDP/SSDP.ino






