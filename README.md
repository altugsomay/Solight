# Solight
Koç University Elec 317 Final Project

This is the final project of Elec 317-Microprocessors class created by Altug Somay in Fall 2015 semester. 

The aim of this project is creating an automated car that has two modes, sound following and light following. As
expected, sound following mode follows sound sources by compairing two sound detector inputs from the Sparkfun sensors.
Similarly, light following mode uses the photoresistor values as inputs and compares them to follow the light source. 

An Atmega32 processor is used as main MCU and programmed in AtmelStudio with Assembly.

Components:

-Atmega32 as main MCU
-L293D as motor controller IC
-Car chassis with 2 DC motors
-2 photoresistors as light sensor
-2 Sparkfun sound detectors as sound sensors
-9V battery as power supplyy
