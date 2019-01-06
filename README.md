# iot-research

## Abstract Idea

- Utilize NodeRed + MQTT + Raspberry Pi 3 to interface with micro-controllers and sensors
  to track simulate and track human movement inside a smart home.
- Research affordances and gain further understanding of how it plays a part

## Hardware

- Raspberry Pi 3 - Model B - Chose one of the two
  1. Raspberry Pi 3 Model B Starter Pack (PRODUCT ID: 3334)
     - This pack will include everything you need
  2. Raspberry Pi 3 - Model B - ARMv8 with 1G RAM (PRODUCT ID: 3055)
     - You will also need to purchse:
        - an 8 GB SD Card to install Raspbian on
        - Power Supply
  - PiTFT - Assembled 480x320 3.5" TFT+Touchscreen for Raspberry Pi (PRODUCT ID: 2097) (optional equipment)
- Keyboard / Mouse
  - wireless w/mouse preferred
- HDMI Cable
  - HDMI to VGA
- Monitor
- Adafruit Feather HUZZAH with ESP8266 (product id: 2821)
  - If not using this device with wireless capabaility, you will need:
    - Adafruit METRO 328 - Arduino Compatible - with Headers - ATmega328 (PRODUCT ID: 2488)
    - Ethernet Shield for Arduino - W5500 Chipset (PRODUCT ID: 2971)
- PIR (motion) Sensor (PRODUCT ID: 189)
- Electronics Parts Pack

## Tasks:

- create an account on tinkerCAD for further understanding of microcontroller circuits
  - https://www.tinkercad.com/
- set up / configure Rasperberry Pi 3
  - set up adafruit PiTFTPlus 3.5" touch screen
  - Resource (1)
- configure MQTT broker on Raspberry Pi3
  - Resource (2.(a/b))
- configure Node RED on Raspberry Pi4
  - Resource (3)

## Software/Downloads

- Raspbian (latest version)
  - installed on the Raspberry Pi
- NodeRed (latest version)
  - installed on the Raspberry Pi
- MQTT Broker (latest version)
  - installed on the Raspberry Pi
- Arduino IDE
  - installed on Mac/PC

## Resources

1. PiTFT

- a. https://cdn-learn.adafruit.com/downloads/pdf/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi.pdf
- b. https://stackoverflow.com/questions/22891235/how-to-change-screen-resolution-of-raspberry-pi

2. MQTT

- a. https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/
- b. https://randomnerdtutorials.com/esp8266-and-node-red-with-mqtt/
- c. https://oneguyoneblog.com/2017/06/20/mosquitto-mqtt-node-red-raspberry-pi/

3. Node-RED

- a. Installation - https://randomnerdtutorials.com/getting-started-with-node-red-on-raspberry-pi/
- b. Cookbook - https://cookbook.nodered.org/
- c. Video - https://www.youtube.com/watch?v=XsR-VTMuaCE
- d. tutorial - https://www.ibm.com/developerworks/library/iot-lp101-get-started-develop-iot-home-automation/index.html

4. Connecting Node-RED to Arduino

- a. https://ktinkerer.co.uk/communicating-arduino-raspberry-pi-using-node-red/
  - i. https://flows.nodered.org/node/node-red-node-serialport
- b. https://www.youtube.com/watch?v=snLZKcecgGI

5. Understanding Node-RED & MQTT

- a. https://www.youtube.com/watch?v=WxUTYzxIDns

6. Node-RED Dashboard
- a. https://www.youtube.com/watch?v=UKv4_jvPtr4

7. Adafruit Feather Huzzah ESP8266
- a. https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/using-arduino-ide
- b. setup mqtt https://randomnerdtutorials.com/esp8266-and-node-red-with-mqtt/ 
