---
date_added: 2020-10-06
model: SLT3
vendor: Hive
title: Heating Thermostat Remote Control
category: hvac
supports: communicate via thermostat
zigbeemodel: ['SLT3','SLT3B']
compatible: [zha,z2m]
mlink: https://www.hivehome.com/products/hive-active-heating
link: https://www.amazon.co.uk/dp/B011B3J6KY
link2: 
link3: 
---
## Pairing instructions

1. Remove the thermostat from the wall and remove a battery
2. Turn boiler off at the mains, this will also turn off the receiver.
3. Turn the boiler on
4. Hold down central heating button on the Hive receiver until light turns pink, then release
5. Hold down the central heating button again until the light turns amber with double flashing
6. Pair with Home Assistant - using ZHA’s ‘add device’
7. At this point the amber double flash may change to a single flash
8. Stop ZHA from searching for devices by pressing back
9. Replace the battery in the thermostat and allow to boot
10. Press and hold the menu and back buttons, allow the countdown to finish and release when you see 'welcome' - after selecting - a language, it will enter pairing mode.
11. On ZHA select the Hive receiver device you added earlier, now click “ADD DEVICES VIA THIS DEVICE”
12. The thermostat should now pair to the boiler receiver. The amber light should turn green.
