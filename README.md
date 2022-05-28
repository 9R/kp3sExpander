# GPIO Expander for KP3S

This PCB is as a replacement for the original LCD-PCB of the KP3S and will 
expose additional GPIOs. It is meant for use with alternative firmware like 
klipper, where the original LCD-PCB is useless.

## Features

* exposes SPI2 (can be used to connect a klipper compatible display)
* exposes 23 additional GPIOs
* access to 5V, 3.3V and GND to power additional sensors
* the original flexible flat cable can be used to connect to the mainboard

## Required Parts

* 1x 32Pin FFC connector (bottom contact, 1mm pitch)

optional:
* pin/socket headers (2.54 pitch, 2x 6x2 + 1x 14x2 for full assembly)
* 15cm 32 pin flexible flat cable (pitch 1mm)

## Example Config

An example config for klipper with an SSD1306 OLED display and a rotary encoder 
can be found in [here](https://github.com/9R/Klipper_KP3S).

## Pictures

#### Top
![top](imgs/kp3sExpander_top.png "Top")
#### Bottom
![bottom](imgs/kp3sExpander_bottom.png "Bottom")
#### Next to original LCD-PCB
![comparison](imgs/kp3sExpander_comparison.jpg "Next to original LCD-PCB")
#### Installed in KP3S
![bottom](imgs/kp3sExpander_installed.jpg "Installed in KP3S")
