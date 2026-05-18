
# BLUERIIOT Blue Connect with ESP Home & Home Assistant

esphome-esp32-blueriiot-connect-homeassistant

BlueRiiot YAML code with ESPHome and ESP32 to work with Home Assistant

This YAML code is an open source created to work with the ESPHome setup in Home Assistant. To be used with your own responsiblity, however it is only reading data from the Blue Connect unit however depending on how many readings done per day can have an impact on the battery.

The yaml code is for the ESP32 and ESPHome to communicate with the unit. 
To trigger readings an Automation in Home Assistant has to be setup. Setup your own schedule.

Setup the ESP32 as any development board before you add the code into your yaml for the unit in ESPHome.

To get your service ID
You need to have your units Service UUID to connec to your specific  
This can be received by using a specific Bluetooth scanner app. Usally availible on Android, Google Play Stor

For presentation on the screen you decide on how you want to display.
There is a custom card on HACS that is a brilliant called pool-monitor-card
https://github.com/wilsto/pool-monitor-card



Enjoy
