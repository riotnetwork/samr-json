# RIOT network  Package Lists for the Arduino v1.6.4+ Board Manager

This repo contains the custom package_*_index.json files that can be used to add new third party boards to the Arduino v1.6.4+ IDE.

Board definitions for RIOT network SAMR based Arduino boards.

IMPORTANT NOTE: These board files have been updated for compatibility with Arduino version 1.8 and higher. Some boards may not compile correctly with earlier versions of Arduino. If you need compatibility with earlier versions of Arduino, you can choose previous releases of these boards from the Boards Manager.

# samr-json
Custom board definition for Arduino IDE to install packages

JSON URL : https://raw.githubusercontent.com/riotnetwork/samr-json/master/package_riot_index.json

* Open your Arduino IDE (V1.6.4 or newer.)
* In Arduino, Click File and then Preferences
* Add the JSON URL to the Additional Boards Manager text box. These are separated by a comma if you are using more than one added board link.
* Click Ok to close and save the preferences
* Then click Tools > Board > Board Manager
* You should see the Manager update on the first time opening after changing the preferences.
* Once updated you should find Riot boards listed in the Board Manager window.
* Find the install button next to this Board class and install.

* Restart Arduino IDE and look under Tools > Boards and you should see the addition of the Riot boards in your board list.

## RIOT R34 Stamp
This core is an arduino port for the Microchip ATSAMR34 and R35 Series microcontrollers - ATSAML21 with integrated LoRa Tranceivers

R34 stamp is designed around Microchip’s ATSAMR34J18 SiP,  a 32-bit Arm Cortex-M0+ MCU (256Kb of Flash, 40Kb of RAM, 8kb of RWW flash) with an internal SX1276 LoRa transceiver. The SiP has a maximum power output of 20.00dBm, a frequency range of 862 to 1020MHz, and a 790nA sleep current.

![R34 pinout](https://github.com/riotnetwork/samr-json/blob/master/Pinouts/PNG/R34-Stamp.png)
