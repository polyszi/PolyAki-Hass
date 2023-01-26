# PolyAki - my Home Assistant Configuration

I am running [Home Assistant Container](https://www.home-assistant.io/installation/#compare-installation-methods) on Unraid OS.

I have setted up following containers: <br/>
[Grafana](https://hub.docker.com/r/grafana/grafana) <br/>
[Influxdb](https://hub.docker.com/_/influxdb) <br/>
[Telegraf](https://hub.docker.com/_/telegraf) <br/>
[Plex](https://hub.docker.com/r/linuxserver/plex) <br/>
[ESPHome](https://hub.docker.com/r/esphome/esphome) <br/>

I use home assistant on two tablet and on 4 phones. The first wall mounted tablet is Huawei Mediapad M10 with [Fully Kiosk Browser](https://www.fully-kiosk.com/#get-kiosk-apps). The second tablet is Apple Ipad 4 mini. This is not mounted yet but it will be done on the next few months in the bedroom. I created two view, one fit with mobil and the otherone fit with tablets.

I have actually some issue with my Windmeter (There was a big rain and the case was not fully IP67, so the water goes in and unfortunately killed my ESP Board) But the newone is on the way, it will be replaced, if I get it.

I inspired from:

[Matt](https://github.com/matt8707/hass-config) here you can find his awesome custom UI. <br/>
[Luke](https://github.com/lukevink/hass-config-lajv) here you can find his awesome Floorplan. <br/>
[IIdar](https://community.home-assistant.io/t/xiaomi-cloud-vacuum-map-extractor/231292/555) - his Xiaomi Robot solution for clean up is the best waht I have ever seen. So I implemented it.

I would like to say thank you guys. Your configuration helped me a lot.

![Screenshot](pictures/home.png)

# Installation:
This is not a theme and you will this not find in HACS.
I share with you my code.
If you want ot use, you have to implement(replace every sensor/ligth/switch with yours)

# Freatures
If someone push the doorbell button, then it will came up in the dashboard a new card and I will get telegramm message - when they push the button date/time and I will also get a picture from my doorbell camera.
![Screenshot](pictures/doorbell.jpg)







https://www.buymeacoffee.com/polyaki
