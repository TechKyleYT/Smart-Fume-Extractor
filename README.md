# Smart-Fume-Extractor
This is an ESP32 based project with a distance sensor to create an automatic "smart" fume extractor. You can quite easily change it to an arduino project by removing things like WiFi and adding a button instead of the web interface.

Necessary libraries:
1. ESPUI: https://github.com/s00500/ESPUI.git
2. WiFi library automatically included with the arduino-ESP32 from espressif

The rest is also mentioned in the ESPUI README, but downloadeble over here for ESPUI:
3. ESPAsyncWebServer: https://github.com/me-no-dev/ESPAsyncWebServer.git
4. ArduinoJson: https://github.com/bblanchon/ArduinoJson.git
5. 1. ESP32: AsyncTCP: https://github.com/me-no-dev/AsyncTCP.git
   2. ESP8266: ESPAsyncTCP: https://github.com/me-no-dev/ESPAsyncTCP.git
