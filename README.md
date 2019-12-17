<div align="center">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif" style="display:block; margin:0 auto;">
</div>

# My Home Assistant Setup:

I run my home assistant instance on a Intel nuc.  The base operating system is [HassOS](https://github.com/home-assistant/hassos). It also runs the following add-ons. 

* [PiHole](https://github.com/hassio-addons/addon-pi-hole)
* [RPC Shutdown](https://www.home-assistant.io/addons/rpc_shutdown/)
* [SSH](https://www.home-assistant.io/addons/ssh/)
* [Samba](https://www.home-assistant.io/addons/samba/)
* [VScode](https://github.com/hassio-addons/addon-vscode)

I'm currently running [Home Assistant](https://home-assistant.io) version __0.102.2__ on this instance.

# UI Based Integrations:
The following integrations are setup in the User Interface (UI) and may be a missing peice as to the full configuration of my HA setup.  

* [MQTT](https://www.home-assistant.io/integrations/mqtt/)
* [Google Cast](https://www.home-assistant.io/integrations/cast/)
* [iOS](https://www.home-assistant.io/integrations/ios/)
* [Zone](https://www.home-assistant.io/integrations/zone/)

# A Few Stats On my Setup:
| Tracked Devices | Lights | Binary Sensors | Switches | Automations | Scripts | Sensors | Zwave Devices |
|:---------------:|:------:|:--------------:|:--------:|:-----------:|:-------:|:-------:|:-------------:|
|35               |10      |7               |33        |77           |6        |150      |8              | 

# Connected Devices:

### Cloud Controlled Devices:

* [Google Home](https://store.google.com/us/product/google_home) Used for voice commands to turn devices on/off and casting a view with a few switches
* [iPhone 11](https://www.apple.com/iphone-11/) Used for presence detection

### Wifi Connected Devices
* [Yeelight RGBW E27 Smart LED Bulbs](http://www.gearbest.com/smart-lighting/pp_361555.html) *
* [Yeelight E27 Smart LED Bulbs](http://www.gearbest.com/smart-light-bulb/pp_278478.html) *
* [Broadlink RM Pro](https://www.gearbest.com/smart-home-controls/pp_255607.html?wid=1433363)*
* [SONOFF Basic R3 WiFi (Flashed with ESPHome)](https://www.gearbest.com/smart-socket-plug/pp_009363914208.html?wid=1433363)*
* [TP Link HS110](https://www.kasasmart.com/us/products/smart-plugs/kasa-smart-plug-energy-monitoring-hs110)*

### Xiaomi Ecosystem
* [Xiaomi Multifunctional Gateway](https://www.gearbest.com/living-appliances/pp_344667.html)
* [Xiaomi Window Door Sensors](https://www.gearbest.com/smart-light-bulb/pp_257677.html)
* [Xiaomi Motion Sensors](https://www.gearbest.com/smart-light-bulb/pp_257678.html)
* [Xiaomi Wall Plug](https://www.gearbest.com/living-appliances/pp_344666.html)
* [Xiaomi Wireless Buttons](https://www.gearbest.com/smart-light-bulb/pp_257679.html)
* [Xiaomi Wireless Wall Switch](https://www.gearbest.com/alarm-systems/pp_610095.html)
* [Xiaomi Temperature and Humidity Sensor](https://www.gearbest.com/living-appliances/pp_344665.html)

### Media
* [Plex](https://www.plex.tv/) for media consumption along with [Plex component](https://home-assistant.io/components/media_player.plex/)
* [Plex activity monitor](https://home-assistant.io/components/sensor.plex/) to track my PMS.
* [Google Cast](https://store.google.com/us/product/chromecast)