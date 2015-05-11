## Description
This directory contains 2 breakout board designs for the ESP8266-01 wifi module. They are aptly named the breakout board and the breakout board minimal. The only real difference is the inclusion of a hardware reset line on the full board. Both boards are meant to be used with the Seeed Grove system. I have chosen this system because of its ease of use at events and for rapid prototyping. It involves no soldering, all the sensors have pre-written libraries, and the mbed.org ecosystem fully supports it. 

#### Full breakout board
This board is the more fully functional of the two and includes a hardware reset line and reset button. The main features are
* hardware reset button / digital I/O line
* two Seeed Grove connectors
* Firmware Update jumper to put ESP chip into firmware update mode

#### Minimal breakout board
This board is minimized for size and ease of use. It uses only through hole parts. 
Features:
- minimal size (cost of less than 1$ per PCB when ordered through OSHPARK)
- TX/RX lines broken out to Seeed Grove Header
- Jumper for Firmware Update mode

Here you can see the Minimal breakout board schematic and board layout files
![Schematic](https://github.com/BlackstoneEngineering/eagle/blob/master/ESP8266%20Seeed%20Breakout%20Board/minimalSchematic.JPG)
![PCBLayout](https://github.com/BlackstoneEngineering/eagle/blob/master/ESP8266%20Seeed%20Breakout%20Board/minimalBoardlayout.JPG)

Here you can see the bare PCB -> assembled PCB -> PCB + ESP8266-01 chip.
![assembly](https://github.com/BlackstoneEngineering/eagle/blob/master/ESP8266%20Seeed%20Breakout%20Board/boards.jpg)

Here you can see the board hooked up to a Seeed Grove shield for use
![seeed](https://github.com/BlackstoneEngineering/eagle/blob/master/ESP8266%20Seeed%20Breakout%20Board/minimalAssembly.jpg)

## Order your own
You can order these PCB's  from oshpark here : 
* [Minimal PCB Page](https://oshpark.com/shared_projects/CQHJGKSS)
* [Full PCB Page](https://oshpark.com/shared_projects/uuOL5hfV )

## Code
To program the boards you can either use a ton of th existing code, or you can take a look at the code i'm working on at [the ESP8266 mbed team page](https://developer.mbed.org/teams/ESP8266). We have examples on using the ESP8266 as a peripheral device over UART and on how to udate the firmware.
