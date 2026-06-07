# Smart Temperature Monitoring System

## Overview

This project was developed as part of the **Maincrafts Embedded Systems & IoT Internship**.

The system uses an Arduino UNO, TMP36 Temperature Sensor, and RGB LED to monitor ambient temperature and provide visual feedback based on predefined temperature ranges.

## Components Used

* Arduino UNO
* TMP36 Temperature Sensor
* RGB LED
* 3 × 220Ω Resistors
* Jumper Wires

## Working Principle

The TMP36 sensor measures ambient temperature and sends analog data to the Arduino UNO. The Arduino processes the data and activates different RGB LED colors according to the measured temperature.

### Temperature Indication

| Temperature Range | LED Color | Status |
| ----------------- | --------- | ------ |
| ≤ 15°C            | Blue      | Cold   |
| 16°C – 30°C       | Green     | Normal |
| > 30°C            | Red       | Hot    |

## Features

* Real-time temperature monitoring
* Visual temperature indication
* Low-cost embedded system design
* Easy to implement and expand

## Applications

* Smart Homes
* Industrial Monitoring
* Greenhouses
* Weather Monitoring Systems
* Educational Projects

## Future Enhancements

* LCD Display Integration
* IoT Connectivity using ESP32
* Mobile Notifications
* Data Logging
* Buzzer Alerts

## Author

Ajitesh Sharma

Embedded Systems & IoT Internship – Maincrafts
