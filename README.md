# VolcaModularMidi
This is a hardware mod to add MIDI IN capability to the [Korg Volca Modular](https://www.korg.com/us/products/dj/volca_modular/)

![Board](https://i.imgur.com/cTA2aZk.jpg)

## Bill Of Materials:
 * R1  220 ohm resistor
 * R2  270 ohm resistor
 * D1  1N4148 diode
 * J1  2.54mm header
 * J2  DIN-5 connector
 * U1  6n139 optocoupler (6n138 and 6n137 should also work as well)

## How to install:

BEFORE YOU BEGIN: 

* This installation process requires you to open your Korg volca Modular, most likely voiding the warranty. The creator of this mod and all the contributors of this project are not to held responsible for possible malfunctions caused by this process.

* In these example photos the mod was already installed (the red/orange/yellow/green cables), but I repeated the process to take the photos and make it easier to explain.

* Read the tutorial and make sure you understand all the steps before proceeding.

Be sure to have the following tools:
  * M3 screwdriver
  * Flat screwdriver (not absolutely necessary but it's useful to unplug the ribbon connectors)
  * Pliers or something to snip and cut thin cables
  * A dril or any tool to open a hole in the case

1-	Unscrew the screws from the back.
![Board](https://i.imgur.com/QdmYQyK.jpg)

2-	Gently pull from a potentiometer to detach the blue case from the circuit.
![Board](https://i.imgur.com/BlXaWwn.jpg)

3-	Unplug the batteries connector (red/black cables) in the top right of the board
![Board](https://i.imgur.com/woWBgqF.jpg)

4-	Lay the circuit down, be careful with the speaker connection (orange/brown cables)
![Board](https://i.imgur.com/s7jFypi.jpg)

5-	You can see the holes now, they're labelled as MIDI_RX, MIDI_TX, +3.3V, GND
![Board](https://i.imgur.com/GZnx0vw.jpg)

6-	Unpeel the black tape and unplug the keyboard connector (white/orange cables)
![Board](https://i.imgur.com/wUcFsOa.jpg)
![Board](https://i.imgur.com/Hk8u4aj.jpg)

7-	Unscrew the 6 screws attaching the main board with the keyboard board.
![Board](https://i.imgur.com/zLBnitX.jpg)

8-	Sit the main board on it's place in the blue case and open a hole on the right side enough to let the four cables go through. Then solder the four cables facing down and snip the excess wire. (disregard the quality of mine, I don't have the tools nor skill for these things :( )
![Board](https://i.imgur.com/olpV5bE.jpg)

9-	Repeat the process from steps 7 to 1 in inverse order to reassemble the unit.

Alternatively if you have the tools, and patience, you can glue the female connections to the case so you can plug it directly (here's a poorly photoshopped concept illustrating it)
![Board](https://i.imgur.com/LGBjef0.jpg)
