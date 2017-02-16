# ESP82XX basic project

Basic firmware and tools to start ESP8266/85 projects based on [esp82xx](https://github.com/cnlohr/esp82xx).

ESP82XX-basic is a stripped down version of [cnlohr](https://www.youtube.com/user/CNLohr)'s [esp8266ws2812i2s](https://github.com/cnlohr/esp8266ws2812i2s), who deserves **all** the recognition.
The ESP8266/8285 chips are products of [Espressif](https://espressif.com) and are awesome "internet of things" solutions.

## Usage

Latetly ESP82XX-basic has been integrated with esp82xx.
Now, the directory structure for a basic firmware is created by cloning this repository and runing `make project`.

   git clone --recursive https://github.com/con-f-use/esp82XX-basic.git
   cd esp82XX-basic
   make project

To actually build firmware, you will need the Espressif toolchain.
Instructions on who to get it and build this firmware are in the esp82xx readme.

## Features

The project provides the following basic funtionality:

 - Web-Interface based on Websockets
 - Network configuration over the Web-Interface
 - Identification of other ESP moules
 - Basic GPIO toggling
 - Flashing of firmware and Web-Interface over Network
 - Fun

