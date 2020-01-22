# README - User guide

## Authors : 

	- Louis-Baptiste Rabillon
	- Ludovic Darguy


## Description : 

In the folder Darguy-Rabillon, you will find two main branches : 
	- Arduino
	- Kicad

Arduino contains source code of Arduino application reading gaz density value of the gaz sensor of our circuit.
First, the application connects to The Thing Network platform thanks to LoRa communication module. 
This application converts the gaz value and then sends it to The Thing Network Platform using TTN Library for Arduino.

Kicad contains all files of designed entities for the PCB conception. We created a library my_library where we added RN2483 module and Gaz sensor footprints and symbols.