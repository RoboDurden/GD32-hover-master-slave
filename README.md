# GD32-hover-master-slave

Based on Hoverboard-Firmware-Hack-Gen2 https://github.com/flo199213/Hoverboard-Firmware-Hack-Gen2

This repository is for Makefile only. I added Makefile, Linker, startup, and Drivers for GD32.

- Makefile is ready
	
	type "make" to compile
	
	type "make flash" to compile and flash

Please see more at the original repository 
	Hoverboard-Firmware-Hack-Gen2 https://github.com/flo199213/Hoverboard-Firmware-Hack-Gen2

#### Hardware
![MasterSlave](https://github.com/weiminshen99/GD32-hover-master-slave/Docs/Hardware_Overview_small.png)

The hardware has two main boards, which are different equipped. They are connected via USART. Additionally there are some LED PCB connected at X1 and X2
 which signalize the battery state and the error state. There is an programming connector for ST-Link/V2 and they break out GND, USART/I2C, 5V on a seco
nd pinhead.

The reverse-engineered schematics of the mainboards can be found here:

![Schematic](https://github.com/weiminshen99/GD32-hover-master-slave/Docs/Schematic.pdf)

---

