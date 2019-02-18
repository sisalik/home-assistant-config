# home-assistant-config
My Home Assistant configuration files for the fairly modest system I have put together so far.

<img src="https://raw.githubusercontent.com/sisalik/home-assistant-config/master/screenshots/screenshot-1.png" />

Features:
- Running on a Raspberry Pi 2 Model B
- 5 wifi-controlled sockets for lights and heating (Sonoff S26 or Basic with the Sonoff-Tasmota firmware)
- DHT22 humidity & temperature sensors and DS18B20 temperature sensors (wired to the Sonoffs or Raspberry Pi)
- Vehicle gate fob connected to Raspberry Pi GPIO via optocouplers (very crudely!)
- Wanhao Duplicator i3 controlled via Octoprint installed on a separate Raspberry Pi 1 Model B+
- Cheap (~£30) bullet-style wifi CCTV camera
- Chromecast and Spotify API

 Additional integrations via <a href="https://tasker.joaoapps.com">Tasker</a> on the phone:
 - SMS-triggered vehicle gate opening for authorised contacts
 - Home/away detection based on wifi and cell connections
 - Automatically turn off lights when going to sleep
 - Quick launch shortcuts in the notification bar using QuickTask
 - 3D printer progress notifications
 - Schedule and alarm clock based heating control
