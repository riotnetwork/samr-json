# samr-json
Ciustom board definition for Arduino IDE to install packages

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

![R34 pinout](https://github.com/riotnetwork/samr-json/blob/master/Pinouts/PNG/R34-Stamp.png)
