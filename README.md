# NSPanel-simple-alarm
Example code and TFT for NSPanel US version to have simple alarm panel.

### alarm.tft
Nextion TFT file, upload it to NSPanel screen.
### nspanel.yml
Example file for ESPHome configuration.
### automations.yml
HA automation to make it all working with Alarmo (well, actually any alarm entity i guess).

---
### UI

* `eu-background.xcf` - Gimp format XCF file to help you layout your custom UI. Set as the background image in Nextion Editor then use `vis <id>,0` to hide it. It shows the section of the screen which is hidden by the bezel in the EU version. The alignment marks take this in to account, so the centre intersection in the image is the centre of the screen on the real device.

---
### References
* https://github.com/sekt1953/HomeAssistant-NSPanel
* https://github.com/dulfer/sonoff-nspanel-esphome
* https://github.com/darktim/ESPHome-NSPanel
* https://github.com/masto/NSPanel-Demo-Files/wiki/HowTo
