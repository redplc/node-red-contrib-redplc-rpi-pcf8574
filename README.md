# node-red-contrib-redplc-rpi-pcf8574

Node-Red node for pcf8574/pcf8574a 8bit I/O Expander<br>

## Node Features
- 8 x Digital Inputs or Digital Outputs
- Inputs with Pullup
- Outputs are Active Low
- Eight selectable Device Addresses for pcf8574
- Eight selectable Device Addresses for pcf8574a

## Install

For using with Ladder-Logic install
[redPlc](https://www.npmjs.com/package/node-red-contrib-redplc) nodes

For using with other nodes, install
[module](https://www.npmjs.com/package/node-red-contrib-redplc-module) nodes

Install with Node-Red Palette Manager or npm command:
```
cd ~/.node-red
npm install node-red-contrib-redplc-rpi-pcf8574
```
## Usage
This node reads/writes from/to Node-Red global variables<br>
Update is triggered by redPlc cpu node or module-update node<br>
This node works only on Raspberry Pi with Raspberry Pi OS<br>
Enable I2C with raspi-config.<br>
Consult datasheet for absolute maximum ratings<br>

### Digital Input (Variable I):
### Digital Output (Variable Q):

|Pin|Bit|
|---|---|
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
