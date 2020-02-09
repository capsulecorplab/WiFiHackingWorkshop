# WiFiHackingWorkshop
> Resources for the WiFi Hacking Workshop

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Prerequisites

Install a terminal emulation program for accessing a serial port based console.

### For beginners
* [Arduino Software IDE](https://www.arduino.cc/en/Main/Software)

### For advanced users

Ubuntu/Debian:

```bash
$ sudo apt install picocom
```

Mac:

```bash
$ brew install picocom
```

Windows:

* [PuTTY](https://www.putty.org/)

## Setup/Installation

This project uses the [WiFi Deauthor](https://github.com/spacehuhn/esp8266_deauther) installed an ESP8266 device - credits to [Stefan Kremser](https://github.com/spacehuhn). For installation instructions, see https://github.com/spacehuhn/esp8266_deauther/wiki

### Serial Interface Setup with Arduino IDE

In Arduino IDE, add this JSON link to the additional board manager URL's list:   

> https://arduino.esp8266.com/stable/package_esp8266com_index.json   

Install the ESP8266 boards in the board manager window.  

Connect your deauther board and select the correct port.  

Select the D1 Mini as the board and open a serial monitor window   

## Usage

* [Web](https://github.com/spacehuhn/esp8266_deauther/wiki/Web)

* [Serial](https://github.com/spacehuhn/esp8266_deauther/wiki/Serial)
