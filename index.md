# Welcome to EnviroMonitor Project

EnviroMonitor is an Open Source, community project to provide air quality metrics using network of community maintained air quality monitors. 

Currently project consists of three modules:

- [EnviroMonitor](https://github.com/EnviroMonitor/EnviroMonitor) - ESP8266 based air quality sensor with budget in mind. You can build it yourself
- [EnviroMonitorWeb](https://github.com/EnviroMonitor/EnviroMonitorWeb) - Django based web backend providing API for sending and receiving air quality metrics. You can host it yourself or use our generally available backend at air-monitor.org
- [EnviroMonitorFrontend](https://github.com/EnviroMonitor/EnviroMonitorFrontend) - Frontend for presenting air quality data from connected sensors

## EnviroMonitor - sensor

EnviroMonitor sensor is a budget, DIY air quality measurment device. It is based on Wemos D1 mini (with famous ESP8266 microcontroller) and PMS3003 particluate matter sensor. It also includes outside temperature, humidity and barometric pressure sensors.  To make measurements even more accurate, we also use heater to exsiccate incoming air.

We also designed PCB so you don't need to use breadboard or other prototype board for your sensor. All designs are Open Source so you can order the board with your favourite supplier.

All components are placed in specially crafted, 3D printed enclosure. We provide all files necessary so you can print it yourself.

Total price for creating EnviroMonitor should not exceed $25.

Sensor can report measurements to [Air-Monitor.org](http://air-monitor.org) (soon to be launched) global website and/or to any website running EnviroMonitorWeb / EnviroMonitorFrontend. We encourage everyone to connect their sensors to our publicly available service so more people can benefit from it.

## EnviroMonitorWeb - web backend

EnviroMonitorWeb is a Django based web backend to manage sensors, air monitoring projects etc. It also provides API to send and read all data regarding air quality monitoring. You can install it on your own server or you can create your local project on [Air-Monitor.org](http://air-monitor.org) (soon to be launched).

Using EuroMonitorWeb you can:

- create your local air quality monitoring project
- add and manage sensors
- manage users
- submit your data through API
- read monitoring data (if you need to present it outside of EnviroMonitor applications)

## EnviroMonitorFrontend - web frontend
