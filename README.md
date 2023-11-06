# Tbogg-Sensor-Package-PCB
The sensor package (strain, temperature, vibration) for the 2024 UofC GNCTR tbogg. Designed as an R&amp;D intrastructure monitoring solution.

## Main Components

1. **2x** Strain Gauge Blocks
	* Ulimately reads one of these two strain gauges:
		1. [100x BF350-3AA](https://www.aliexpress.com/item/595240806.html)
		2. [10x BX120-2AA](https://www.aliexpress.com/item/1005003672107724.html)
	* Based on [this schematic](https://www.elecrow.com/strain-gauge-module-p-735.html)
	* Sensing via HX711 chip
2. **1x** On-PCB Temperature Sensor (STDS75DS2F)
	* I2C
3. **4x** In-Concrete Temperature Sensors
	* Get from BIRDS-X board
	* I2C Comms
4. **1x** Vibration Sensor
	* Model: MPU-6050 Breakout
	* I2C Comms
5. I2C Optical Flow Sensor
6. Battery: nx 18650
	* TODO: choose quantity, model, holder, and connection
7. Battery Management System: probably the 3V3 buck-boost from the balloon project
	* TODO: more info
8. Wireless Comms: LoRa Wio E5
	* TODO: pull from balloon project
	* TODO: confirm that this model is good
9. Microcontroller Unit (MCU)
	* ESP32 Breakout

## Reference Links
* TODO: fill

## Revision Notes
* PCB orders will each recieve a new revision number. 
	* PCB orders will be in the format of "Rev1", "Rev2", etc.
	* GitHub Releases (and Tags) will be tagged in the format of `rev1`, `rev2`, etc.
* BOM changes on PCB orders should be documented as minor revisions.
	* Example: `rev1.1`, `rev1.2`, etc.
