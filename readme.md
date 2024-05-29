# Bare Conductive Arduino Hardware Plugins
This package is a combination of different reqirements to make your Bare Conductive Board work with the Arduino IDE : https://github.com/BareConductive

Board definitions for Bare Conductive Arduino-compatible boards, needed to use the [Bare Conductive Touch Board](http://www.bareconductive.com/touch-board) with full functionality in the [Arduino IDE](http://arduino.cc/en/main/software). 

## Requirements

* Arduino 1.6.6 or later


## Install the Hardware

1. Close the Arduino IDE if you have it open.
2. Download the zipped Repository https://github.com/MediaDock/BareConductiveStarterPack/ or clone the repository to your local machine - if downloading the .zip, extract the contents somewhere that suits you.
3. Install the Hardware: 
Drop the Contents of the hardware Folder (bare-conductive-arduino-public) into the hardware folder of your Arduino folder. If you don`t have a hardware Folder inside the Arduino Folder on your Computer Drop open up a new one. The name of the folder should contian all small letters: hardware.
Take the **bare-conductive-arduino-public** folder and move it to **Arduino Hardware Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino\\hardware
	
	or
	
	My Documents\\Arduino\\hardware
	
	**Mac**
	
	Documents/Arduino/hardware
	
	**Linux (Ubuntu)**
	
	Home/Arduino/hardware

4. Reopen the Arduino IDE - you should now be able to select Bare Conductive Touch Board in the **Tools -> Board** menu.


## Install the Libraries

1. Close the Arduino IDE if you have it open.
2. Open the Downloaded Repository again.
3. Install the Libraries: 
Drop the Contents of the libraries Folder (MPR121, SFEMP3Shield, SdFat) into the libraries folder of your Arduino folder. If you don`t have a libraries Folder inside the Arduino Folder on your Computer Drop open up a new one. The name of the folder should contian all small letters: libraries.
Take the **MPR121, SFEMP3Shield, SdFat** folders and move them to **Arduino Libraries Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino\\libraries
	
	or
	
	My Documents\\Arduino\\libraries
	
	**Mac**
	
	Documents/Arduino/libraries
	
	**Linux (Ubuntu)**
	
	Home/Arduino/libraries


	If this folder does not exist, create it first.

4. Now you should have the most exotic libraries installed to run the Touch_MP3 Example. If you need other Libraries, try to find them ofer Libraries Manager of the Arduino IDE. 


## Install the Examples

1. Close the Arduino IDE if you have it open.
2. Open the Downloaded Repository again.
3. Install the Examples: 
Drop the Contents of the examples Folder (Touch_MP3) into the examples folder of your Arduino folder.
Take the **Touch_MP3** folders and move them to **Arduino Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino
	
	or
	
	My Documents\\Arduino
	
	**Mac**
	
	Documents/Arduino
	
	**Linux (Ubuntu)**
	
	Home/Arduino


	If this folder does not exist, create it first.
	
4. Reopen the Arduino IDE - you should now be able to select the Example Touch_MP3 in the **File -> Examples** menu.