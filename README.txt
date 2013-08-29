
The RGB LED SHIELD from www.Re-Innovation.co.uk is designed to control high current RGB
LED boards such as those available from www.phenoptix.co.uk / www.bigclive.com

These are the PCB and Arduino code files for the RGB LED Shield.

This PCB was designed by Matt Little of www.re-innovation.co.uk
Contact: info@re-innovation.co.uk

And is sold by Phenoptix www.phenoptix.com

Details and diagrams are available at:

The PCB files were created in KiCAD PCB design software

The Shield is designed to fit onto an Arduino microcontroller.
Example code has been written for the Arduino IDE


Overview of the design:

  A WS2801 RGB LED control IC is used, which holds the state of the LEDs.
  The outputs can control up to 1.5A per channel - enough for loads of LEDs
  
  The example code will gives a number of examples of how to control the output:
  
  First is scrolls through RED GREEN BLUE for 2 seconds each
  
  It then fades between RED GREEN BLUE
  
  It then uploads a number from a random seed and displays the colour, changing every 0.5seconds
  
  The Shield has the SDI connected to Arduino pin 9 and the CKI connected to Arduino pin 8.

    
  The Arduino code is based upon code from: Nathan Seidle
  SparkFun Electronics 2011
 

Modified:
29/8/13	GitHub Repository created - Matt Little
 
