Blueberry PI 7.1
================

Added:
------
* LVDS interface with cheap SN65LVDS84 serialiser,
* resistive touchscreen controller TSC2003 + pinheader for resistive touch,
* flash w25q128,
* more popular MicroSD card slot,
* datasheets for them

Removed:
--------
* pinheader for OV7670


Blueberry PI
============
Another fruit single board computer (SBC), based on the Allwinner V3s system on a chip (SOC). 
The Allwinner V3s comes in an easy to solder 128pin TQFP package. 

The Blueberry PI features: 

- 100 mbps Ethernet 
- 1 USB Host Port / 1 mini USB port 
- MIPI CSI interface (unfortunately no support in the linux kernel yet) 
- Pinheader for an OV2640 and an OV7670
- Wifi and bluetooth 
- RGB interface for connecting displays 
- Audio jack 
- an onboard microphone 
- four buttons for play, pause, next and previous 
- a Raspberry PI compatible header
- SPI Flash
- SD card slot


The Blueberry PI can boot from an SD card or SPI Flash. 
Since the V3s doesn't have a standard video output, I'm planning on creating a video addon board which provides VGA or HDMI. In combination with the ADV7611 it is possible to capture HDMI.

If you have any questions email me at marcel[dot]thuermer(at)smail[dot]emt[dot]h[minus]brs[dot]de
