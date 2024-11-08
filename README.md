# ESPHome-Zehnder-RF

## Fork notes
I'm using an ESP8266 NodeMCU V2 board to control a Zehnder ComfoFan S. Make sure to follow the PIN structure. See my actual `utility-bridge.yaml` file in my [Home Assistant repository](https://github.com/DevSecNinja/home-assistant-config/blob/main/esphome/zehnder-rf.yaml).

- The pairing didn't work for me after trying many forks. Disconnecting the CE (D2) PIN worked for me and suddently the device started to work!

### Known issues
- [ ] The CO2 sensor overwrites any actions I provide, despite the broadcast fix.
