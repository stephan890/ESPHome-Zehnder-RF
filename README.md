# ESPHome-Zehnder-RF

## Fork notes
I'm using an ESP8266 NodeMCU V2 board to control a Zehnder ComfoFan S. Make sure to follow the PIN structure. I'll update the `utility-bridge.yaml` file with my config once I have it all worked out. Below my notes that you can't get from the code:

- The pairing didn't work for me after trying many forks. Disconnecting the CE (D2) PIN worked for me and suddently the device started to work!

### Known issues
- [ ] The sensor data in Home Assistant is not getting updated after a reboot. I need to click e.g. "High 30 minutes" before it instantly gets updated.
- [ ] The CO2 sensor overwrites any actions I provide, despite the broadcast fix.
