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

