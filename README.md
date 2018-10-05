## README ##
***

### Overview ###

Wildlife biologist currently use Radio-telemetry to obtain information on the movement of a focal species. Radio-telemetry is a very effective tool however the procedure associated with its usage is very inefficient. Typically a large metal antenna is connected to a VHF radio telemetry transmitter and taken into the field, then the procedure goes as follows: 
* The range of the transmitter is set to the max and the antenna is pointed in all directions until a beep is heard
* The researchers head in that direction and decrease the range 
* The area is scanned, the researchers move in the direction of the beep, and the range is decreased
**This step is repeated until the animal is found, which could take many HOURS**
In addition, Radio-telemetry can inﬂuence the behavior of the animal when frequent measurements are required. 


Global Positioning System (GPS) technology can be used to gather larger data sets that are more accurate much more efficiently. However, the main limitation to the widespread of this technology is the cost. Commercial wildlife GPS trackers cost on average between $2000–$8000, USD, with a bunch of hidden costs. Using open source hardware and software a low-cost GPS logger can be made with basic tools and a basic understanding of electronics

### Hardware Description ###

The Logger is made up of 3 major components; an Arduino Pro Mini, GPSRM module, Lithium-ion battery and a custom designed PCB responsible for powering peripherals and storing data.

![webp net-resizeimage](https://user-images.githubusercontent.com/24802401/46558438-174a8780-c8bb-11e8-980e-1c13bab4512d.png)
             ![webp net-resizeimage 1](https://user-images.githubusercontent.com/24802401/46558608-ad7ead80-c8bb-11e8-8fae-a488e478b079.png)

* The components were arranged to minimize the height of the logger to reduce its footprint.

* Black Heat shrink tubing was used to protect and water proof the logger
 


![webp net-resizeimage 2](https://user-images.githubusercontent.com/24802401/46558700-02babf00-c8bc-11e8-9e45-bf37d06c8a8d.png)

A logger placed on the shell of a snapping turtle 


### Software Description ###
