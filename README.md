# Dispenser Controller

This is the schematic for the current source which will drive the Cesium dispensers.
We have 2 sets of dispensers, so this module has two independent current sources.
This module requires a high current power supply channel.

A panel mounted voltmeter is used to monitor the current.
A 5A fuse is used to put a hard limit on the current into each dispenser.
For extra safety, this module is not connected to the microcontroller at all.
It is instead controlled with a panel-mounted locking potentiometer.
