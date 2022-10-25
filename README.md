<h1>abrIoT SD Card Image for Olimex-A10</h1>

<h2>Dowload</h2>

Disk image is a large file, 1.83GB and, therefore, is downloadable from our Google Drive folder.

<a href="https://drive.google.com/drive/folders/1txmobx2sUAEdND8ckU6oaFwQzqN48iTZ?usp=sharing" download>DOWNLOAD OLIMEX A10 DISK IMAGE</a>


<h2>What is this image for?</h2>

This SD card image is a complete image for Olimex A10 Linux single board computer (SBC). For information about the board, please refer to www.olimex.com.

The image lets you to use the board for home automation purposes with great flexibility.

The energy consumption of the board is very low, it works with a 5V power supply. The total memory usage is around 200MB (depends on the data stored on the SD card).

<h2>The content of the package</h2>

The image contains the following packages:
- Linux Debian minimal installation (based on Olimex public disk images). I.e. no graphical interface www.olimex.com
- Node-RED installation with modbus and email nodes www.nodered.org
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

<h2>Utilization of the board</h2>

The image is aimed for home automation purposes. Olimex A10 may serve as a home automation server with the image installed.

It can be used as:
- A modbus master: polling data and controlling modbus slave devices via modbus RTU or TCP. For modbus RTU, you will need a RS485 to USB converter
- An MQTT borker: collecting data via MQTT protocol from local devices
- A data log: by using InfluxDB, tons of metrics may be stored and analyzed later (e.g. temperature, humidity, energy consumption etc.)
- A gateway for web-based APIs like Open Weather Map or Spotify
- As a custom API: receiving and sending remote commands via ethernet by using hash algorithms (e.g. SHA-512)
- An MQTT subscriber: sending and receiving data to and from public MQTT brokers
- A device for primitive local AI: recognizing images and commands (e.g. with TensorFlow), analyzing home conditions and making predictions or decisions (e.g. with regressions)
- A music center: playing music or sounds (like doorbell)
- A security and alerting device: collecting data about the property (energy consumtpion, door/windows state, movement, smoke or fire) and sending alarms via different channels like email, Messenger or Telegram
- A HMI interface: Node-RED UI allows the development of custom interfaces. You may use JavaScript, HTML and CSS to desing custom webpages and publish them on a local webserver

<h1>Languages and Tools</h1>

<div>
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/Debian.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/NodeRED.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/JavaScript.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/HTML.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/InfluxDB.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/MQTT.png" height="80px" width="80px">
  <img src="https://github.com/abrIoTeu/abrIoTeu/blob/main/modbus.png" height="80px" width="80px">
</div>

---

Linux Debian, Node-RED, JavaScript, HTML, InfluxDB, MQTT, modbus

<h1>Contact</h1>

<a href="mailto:abriot.eu@gmail.com" target="_blank">abriot.eu@gmail.com</a>
