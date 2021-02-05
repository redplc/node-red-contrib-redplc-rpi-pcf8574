# node-red-contrib-redplc-rpi-pcf8574

redPlc module node for PCF8574/A 8bit I/O Expander.<br>

## Install

[redPlc use this module node. Install redPlc.](https://www.npmjs.com/package/node-red-contrib-redplc)

[If you use this node for other nodes install this.](https://www.npmjs.com/package/node-red-contrib-redplc-module)

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-rpi-pcf8574
```
## Usage
Wire this node to first output of redPlc cpu node.<br>
Global variable I are updated with digital inputs.<br>
Global variable Q sets digital output.<br>
For PCF8574 use address 20H - 27H<br>
For PCF8574A use address 38H - 3FH<br>
This node works only on Raspberry Pi with Raspberry Pi OS.<br>
Enable I2C with raspi-config.

### Digital Input (Variable I):
### Digital Output (Variable Q):

|Pin|Bit|
|:--|:-:|
|P0|0|
|P1|1|
|P2|2|
|P3|3|
|P4|4|
|P5|5|
|P6|6|
|P7|7|

## Donate
If you like my work please support it with donate:

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZDRCZBQFWV3A6)
