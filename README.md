# The GarlicBoard
A different sort of keyboard by
Tom "stiligFox" Meyer

(c) tommeyer 2017

PCB v1.0_20170531
ReadMe v0.1_20170824

First write up

The KiCAD Libraries are (c) their original authors, and I greatly thank them for their invaluable assistance in designing this board!

The Funkydori font is (c) Laura Worthington and may not be reused without liscene and permission. http://lauraworthingtontype.com/family/funkydori/ Many thanks to her for designing such a great font!

# Instructions
Please be sure to read everything here before beginning! You may have a better way of doing things than the way I did.
# Assembling the PCB
* Teensy
Please view this gallery of images:
LINK
Please note, this is how I did it; you may find an easier way. The main point is to keep the Teensy as flush with the PCB as possible. There is no circuitry under the Teensy to worry about shorting; however, take care not to damage the silkscreen layer as there is insulation copper underneath.
  1) Break up your headers into chunks of 2.
  2) Align them through the back of the Teensy, long end first, organized as shown. It helps to tape the Teensy and pins down at this time.
  3) Put the Teensy and pins into the PCB, with the Teensy going on the side that says "GarlicBoard."
  4) Solder the pins on the PCB side.
  5) Flip the board over and remove the tape and Teensy.
  6) Using pliers, carefully pull up on the plastic as shown to remove header spacers. This is the reason we broke them up earlier.
  7) Place the Teensy back into the pins, and snug it down as far as it'll go.
  8) Solder the Teensy in place, and then clip the pins short (Not shown). It may help, in hindsight, to clip the pins short and then solder the Teensy in place. One issue I've run into is that the pins will loosen from the PCB and sag a bit.

* Diodes
Diodes are soldered onto the board with the | directional line pointing to the left (Towards the numpad, see image). The text "T4" should also be right side up.
  * IMPORTANT NOTE: The two spacebar diodes do not follow this rule; they are upside down.
  * Image: 

* Resistors
  * Resistors are for the 4 LEDs; their positions are marked by "R" on the front side of the PCB.
  * The orientation of the resistors does not matter.
  * See this video for the varying levels of brightness; the dimmest is a 1500ohm resistor, the brightest is a 150ohm. The ones in between are the varying levels included with the kit.
  
* LEDs
  * Included are orange LEDs. The | line points to the north on the top three LEDs, and it points to the south on the bottom LED.
   * Image:
  
# Case Files
* The plate files that I designed can be downloaded in the GarlicBoardCaseFiles.zip. They are my current design for a very slim sandwhich board that leaves little margin for error; this is just a sample design and probably not ideal.
* You can use these two sites for your plate design:
  * http://www.keyboard-layout-editor.com/#/gists/deefedea4f1e6f569e215b70d19be315
  * http://builder.swillkb.com
* The plate SVG in the  however, is built off of the layer from the actual kiCAD design files; it is what I used when I had my plate cut. If you use the swillkb.com tool, I recommend printing it out on paper before hand to make sure that all of the holes line up.
* OTHER NOTES:
  * The PCB needs to have four 2mm x 2mm holes centered over the LEDs.
  * The LightChannel files are designed to stradle over the LEDs in an upside down position and insert into the plate as seen here.
    * Image:
    * It may help to use something such as rubber cement to hld the light channels into place.
  * 
  
# Firmware
* The firmware is currently still in beta. It is being
