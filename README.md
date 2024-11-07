# Group24

Aim:To Read serial data from GPS module and print the current datea and time.

Problem Statement: To develop a GPS data display system using a Tiva C Series microcontroller. The system will recieve GPS data via UART, prase NMEA sentences to extract date,time,speed and position.This will enable realtime tracking and display of essential GPS data.


Block Diagram:
[GPS Module]-----Serial Data (UART)---[TM4C123GH6PM (UART Receiver)]---NMEA Sentence Data---[NMEA Sentence Parser]---Extract information---[Data Selector]---Print to Serial Monitor----[Display Module]
