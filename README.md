# Smart-Garage-Controller
Whatch this space for updates on the new Smart Garage Controller.

![Image of SmGar Controller Top](https://github.com/HomeAutomationsXYZ/Smart-Garage-Controller/blob/main/SGC_V1_0_Top.JPG)

![Image of SmGar Controller Bottom](https://github.com/HomeAutomationsXYZ/Smart-Garage-Controller/blob/main/SGC_V1_0_Bottom.JPG)

## Features
* Support for Centurion SD04 Smart Motor
* Open / Close Garage Doors
* Get status of Garage Doors
* 2x Configurable LEDs (Top and Bottom)
* Temperature and Humidity Measurement
* Ambient Light Measurement
* Optional Vehicle Detection (1 or 2 Vehicles)
* Optional Presence Detection
* Optional Movement Detection
  - Supported mmWave sensors:
    - LD-2402
    - LD-2420
    - LD-2410C
    - LD-2410B
* Additional GPIO's exposed
* Bluetooth on ESP32
  - Used for Bluetooth Proxy
  - Other Bluetooth Features

## Home Assistant Basic view

![Image of basic view in Home Assistant](https://github.com/HomeAutomationsXYZ/Smart-Garage-Controller/blob/main/HA_View_1.jpg)

View above includes:

* ESP32-WROOM with Bluetooth
* Door status (Open/Closed) using Reed Switch
* Trigger door to open/close
* Temperature and Humidity Sensors
* Ambient Light Sensor
* LD-2402 mmWave Sensor
  - Binary Presens
  - Micro Movement Detection
  - Distance to Human
* HC-SR04 Ultrasonic Distance Sensor
  - Measures distance to floor / car
  - Determine if Vehicle is present in garage

## Notes
* Running ESPHome for Home Assistant Integration
* Local-Only Control
* 3D Printable Case for easy mounting
  
