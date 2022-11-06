# CANBurner

This Project originated from the idea of making the swaping process of the Stealthburner front easier. 
Canburner is a PCB design, that works in cooperation with Hartk's 2pc PCB design. 

It consists of a frontpart and our adapted CANBurner
The CANBurner is the connection PCB between an EBB36 or EBB42 or any CAN module and the movable front PCB.
over the course of the revisions functions were added and the design was changed. 

# Changelog:
## Rev 1.0 (initial design; tested) 19.10.2022
- adapted the footprint of Hartk's Backplate to fit for our purpose
- JST-XH connectors for 2x fans (Hotend and Partcooling) and 1x LED added
- 2x3 angled pin headder to connect to the front PCB 
- simple wirepaths over the board
- a throughhole design for easy soldering at home

first tests by André show, that the design fits perfectly on the CW2 extruder. dimensions reach barely past the motorbackplate. 
THD components dont collide with eachothe or the SB. Functions are fully present and the JST connectors make swapping cables easy.
Space can be used more effectively. JST is not as important, the cables can be soldered directly on the Board.

## Rev 2.0 04.11.2022
- Name CANBurner was suggested by rootiest
- added one more JST-XH for I2C connection
- added 2x4 angled pin headder 
- placement of connectors were changed
- added Voron Logo 
- minor cleanup of traces and text

## Rev 2L 05.11.2022
- added Neopixel SMD light as status LED
- changed traces
- added voltage testpoints for 24V, 5V and GND
- added "rootiest"-Logo

## Rev 3
- fully changed plug design
- one 8 pin jst to connect to CAN board
- 4 pin socket headder to allow for direct I2C connection
- SMD LED and solder traces to skip LED when its ot used
