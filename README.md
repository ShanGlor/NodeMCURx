# NodeMcuRx
Drone/Quadcopter receiver using NodeMCU to be controlled using a web browser (8 channels).

Using Arduino IDE, upload the two sketches:
Multiwii22 for Uno, nano or promini
And NodeMcuRx for NodeMCU->select NodeMCU 1.0 (ESP-12E module) as board.

On Android or iOS Settings->WIFI
Refresh- 
Connect to "WifiPPM" hotspot
Password is "Wifi_PPM" (without the quotes)

Open a web browser (Safari, Chrome or Firefox)
Type in address bar "192.168.4.1"

Use MultiWiiConf to config Multiwii (i.e. PID settings)

Schematics https://github.com/ShanGlor/NodeMcuRx/blob/master/schem.png
