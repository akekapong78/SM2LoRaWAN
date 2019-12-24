# SM2LoRaWAN
PSU LoRa LAB

OBJECTIVE
  This lab shows the LoRaWAN networking to send the Smart Meter (SM) data using the CAT LoRa server and the Node-Red application. This is a basic system for the Internet of Things (IoT) application or the Wireless Sensor Network (WSN).

OVERVIEW
  LoRaWAN is a media access control (MAC) protocol for wide area networks. It is designed to allow low-powered devices to communicate with Internet-connected applications over long range wireless connections. LoRaWAN can be mapped to the second and third layer of the OSI model. It is implemented on top of LoRa or FSK modulation in industrial, scientific and medical (ISM) radio bands. The LoRaWAN protocols are defined by the LoRa Alliance and formalized in the LoRaWAN Specification which can be downloaded on the LoRa Alliance website.
  •	End Device - an object with an embedded low-power communication device.
  •	Gateway - antennas that receive broadcasts from End Devices and send data to LoRa server.
  •	Network Server - servers that route messages from End Devices to the right Application.
  •	Application - a piece of software, running on a server.

MATERIAL
  ·	LoRa End Device                   (www.st.com/resource/en/data_brief/b-l072z-lrwan1.pdf)
  ·	LoRa Gateway (CAT)              	(fccid.io/MCLGPE810U/User-Manual/Users-Manual-3393820)
  ·	LoRa Network Server (CAT)  	      (https://loraiot.cattelecom.com/portal/login)
  ·	Arduino IDE 1.8.9                 (www.arduino.cc/en/main/software)
  ·	ArduinoCore-STM32 library	        (github.com/grumpyoldpizza/ArduinoCore-stm32l0)
  ·	ST-Link USB drivers	              (www.st.com/en/development-tools/stsw-link009.html)
  ·	Node-Red API	                    (https://nodered.org)
  ·	MQTT protocol	                    (https://www.cloudmqtt.com/)
  ·	Smart Meter(Mitsubishi SX1-A31E) (https://www.meath-co.com/meter/product_detail.php?id=65&catID=15)
  ·	MAX485 Module TTL to RS485        (https://www.arduitronics.com/product/692/max485-module-ttl-to-rs485)
