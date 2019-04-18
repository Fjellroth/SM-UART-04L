# SM-UART-04L
I have created this with almost no coding background using code created by far better programmers.
Sensor data sheet- https://www.mouser.com/catalog/specsheets/Amphenol_12202018_AAS-916-139A-Telaire-SM-UART04L-AppNote-102018-web.pdf

This repository contains a sketch for SM-UART-04L Laser dust sensor and a Python script which performs serial read and write to CSV file for Pi
The code within this repository is being used to record particulate matter data from two Laser dust sensors.

The hardware is an Arduino MEGA 2560 and a Raspberry Pi 3 B+.

On the Arduino the data pins from each sensor are connected to pins 17RX2 and 19RX1, these can be modified.

The raspberry Pi is basically just being used as a data logger: https://makersportal.com/blog/2018/2/25/python-datalogger-reading-the-serial-output-from-arduino-to-analyze-data-using-pyserial
