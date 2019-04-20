# FAIO-Sip-And-Puff Switch 

FAIO Multiplexer is an open-source Assistive technology wing for Adafruit Feather boards which enables those with limited or no hand movement to use Sip and puff as an input method to replace both keyboard and mouse.

FAIO Multiplexer supports following modes:

* Morse Keyboard Mode ( HID Keyboard )
* Morse Mouse Mode ( HID Mouse )


# Downloads 

These are all the files and documentation associated with the FAIO Sip-And-Puff project.

 <table style="width:100%">
  <tr>
    <th>Resource</th>
    <th>Version</th>
    <th>Format</th>
    <th>Link</th>
  </tr>
    <tr>
    <td>FAIO Multiplexer All</td>
    <td>2.0</td>
    <td>ZIP</td>
    <td><a href="https://github.com/milador/FAIO-Sip-And-Puff/archive/master.zip">FAIO-Sip-And-Puff-master.zip</a></td>
  </tr>
  <tr>
    <td>FAIO-Sip-And-Puff Manual</td>
    <td></td>
    <td>PDF</td>
    <td><a href=""> </a></td>
  </tr>
  <tr>
    <td>FAIO-Sip-And-Puff Switch BOM (csv)</td>
    <td>February 18, 2019</td>
    <td>CSV</td>
    <td><a href="https://github.com/milador/FAIO-Sip-And-Puff/blob/master/Components/FAIO-Sip-And-Puff_BOM.csv">FAIO-Sip-And-Puff_BOM.csv</a></td>
  </tr>
  <tr>
    <td>FAIO-Sip-And-Puff USB Software</td>
    <td>1.0</td>
    <td>Ino</td>
    <td></td>
  </tr>
  <tr>
    <td>FAIO-Sip-And-Puff Switch Board Layout</td>
    <td>1.0</td>
    <td>BRD</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO-Sip-And-Puff/master/Hardware/PCB_design/FAIO-Sip-And-Puff.brd">FAIO-Sip-And-Puff.brd</a></td>
  </tr>
  <tr>
    <td>FAIO-Sip-And-Puff Switch Board Schematic</td>
    <td>1.0</td>
    <td>SCH</td>
    <td><a href="https://raw.githubusercontent.com/milador/FAIO-Sip-And-Puff/master/Hardware/PCB_design/FAIO-Sip-And-Puff.sch">FAIO-Sip-And-Puff.sch</a></td>
  </tr>
</table> 

# Usage

The FAIO-Sip-And-Puff interface can operate in 2 modes and 3.5 mm switch is used to switch between keyboard mode and mouse mode. 
The switch is also used to switch it between USB and Bluetooth when it's in configuration mode. The RGB Led blinks 2 times to indicate the current mode.

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/FAIO-Sip-And-Puff/master/Resources/Images/faio_sipandpuff.png" width="50%" height="50%" alt="FAIO-Sip-And-Puff"/>
</p>

## USB or Bluetooth Switch mode

 <table style="width:100%">
  <tr>
    <th>Mode Number</th>
    <th>Mode</th>
    <th>Color</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Morse Keyboard</td>
    <td>Pink</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Morse Mouse</td>
    <td>Yellow</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Configuration</td>
    <td>Purple</td>
  </tr>
</table> 


## Software Setup Instructions

  1. Install the required libraries 
  
  1.1. Install Neo Pixels : https://github.com/adafruit/Adafruit_NeoPixel

  1.2. Install EasyMorse if using USB or Bluetooth version : https://github.com/milador/EasyMorse
  
  1.3. Install StopWatch if using USB or Bluetooth version : https://github.com/RobTillaart/Arduino/tree/master/libraries/StopWatch
  
  1.4. Install FlashStorage if using Feather M0 Board : https://github.com/cmaglie/FlashStorage
 
  2. Download the firmware 
  
  2.1. USB Firmware (Coming up)
  
  2.2. Bluetooth Firmware (Coming up)
  
  3. Setup Arduino IDE for your feather board according to the instructions on Adafruit website
  
  4. Verify and upload firmware code to your Feather Board
