<h1>abrIoT SD Card Image for Olimex-A10</h1>

<h2>What is this image for?</h2>

This SD card image is a complete image for Olimex A10 Linux single board computer (SBC). For information about the board, please refer to www.olimex.com.

The image lets you to use the board for home automation purposes with great flexibility.

The energy consumption of the board is very low, it works with a 5V power supply. The total memory usage is around 200MB (depends on the data stored on the SD card).

<h2>The content of the package</h2>

The image contains the following packages:
- Linux Debian minimal installation (based on Olimex public disk images). I.e. no graphical interface www.olimex.com
- Node-RED installation www.nodered.org
- Mosquitto MQTT borker installation www.mosquitto.org
- InfluxDB installation www.influxdata.com

The image also contains the following setups:
- SSH allowed (port 22)
- Ethernet connection allowed and setup (by default, this is denied in Olimex)
- Ports 22, 1880, 1883, 8085 are open in order to allow communication with the board
- A static IP of 192.168.0.80

<h2>Installation</h2>

Just download the image and use a disk imager software to burn it to a micro SD card (at least 8GB is reccommended). Inster the card into Olimex A10 and power up the board.

Login
user: olimex
password: olimex

<h2>Accessing the board</h2>

You may access the board by SSH or by connecting a keyboard to the USB port and a screen to the HDMI port.

The default IP for the board is 192.168.0.80 -> this and other ethernet settings may be changed anytime later.
