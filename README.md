# ESP-Now-AsycnWebServer
ESP3-Now AsyncWebserver fed by remote sensor sender to ESP-Now receiver on mains power.  ESP32_Sender now uses NTP for syncing events with ESP32 Receiver.

Completed adding ESP-Now to "Rain Gauge" project; now with the capability of having sensor on separate ESP32, sender outside and ESP32, Receiver inside. Inspired by https://randomnerdtutorials.com/esp-now-two-way-communication-esp32/ Randomnerd's Tutorial. ESP-Now is supported in this project.
Dash board has not been verified; as it is coded for three ESP32's and a different sensor, planning to add additional ESP32, sender boards at a later date.  Tutorial uses, three ESP32 boards; currently have two ESP32 boards.  https://randomnerdtutorials.com/esp-now-esp8266-nodemcu-arduino-ide Using  ESP8266 with ES-Now[/url] tutorial.  Have not explored this possibility; likely will at a later date.

Project features: AsyncWwebSserver that drives two websites, Time events are driven by NTP time servers, FTP, Over-the-air firmware updates, Logging of Data, Wi-Fi restart events, server restart events, and watch dog restart events –all time stamped.

Edit "variableInput.h" found in the ESP-Now recevier folder with your network credentials network server ip, gateway, netmask, and dns.  

Project is in development; Dash board is non-functional my code.  

 
