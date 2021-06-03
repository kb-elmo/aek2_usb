# AEK II USB

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

#### QMK compatible drop-in replacement PCB for the Apple Extended Keyboard II
The PCB is built entirely with THT parts to keep a somewhat "vintage" look to it and it uses the fullsize 40-pin DIP package ATmega32A.
The controller is placed in the exact same location as the one on the original PCB.

<img src="https://files.elmo.space/kicad_images/aek2_usb-Front.png" alt="drawing" height="300"/>
<img src="https://files.elmo.space/kicad_images/aek2_usb-Back.png" alt="drawing" height="300"/>

### Partslist
Most of the parts in this list are just examples and they can be replaced with any component with the same specs.  
They don't have to be from any specific manufacturer or brand to work on this board.

The USB breakout PCB/Daughterboard is NOT included in this repo. You will have to find one yourself.  
Pretty much any kind of breakout board that has usable VCC, GND, D+ and D- pins should work for this.  
Example: https://www.adafruit.com/product/1764

|Count|Part|Designator|Octopart URL|
|-|-|-|-|
|1|ATmega32A 40 pin DIP (32L works too)|U1|[Atmega32a-pu](https://octopart.com/atmega32a-pu-microchip-77760288)|
|1|40 pin DIP socket (optional but highly recommended)|U1|[TE Connectivity 1-2199299-5](https://octopart.com/1-2199299-5-te+connectivity-34963610)|
|1|2x3 pin header 2.54mm (for ISP flashing)|AVR1|[Würth 61200621721](https://octopart.com/61200621721-würth+elektronik-32855457)| 
|1|JST PH 2mm 4pin connector + cable|J1, J2|[JST S4B-PH-K-S](https://octopart.com/s4b-ph-k-s+%28lf%29%28sn%29-jst-5373077)|
|1|USB breakout PCB|||
|1|500 mA polyfuse|F1|[Bourns MF-R050](https://octopart.com/mf-r050-bourns-19418)|
|2|6mm momentary push buttons|RESET1, BOOT1|[TE Connectivity 1825910-6](https://octopart.com/1825910-6-te+connectivity-42270338)|
|1|16 MHz quarz crystal|XTAL1|[Raltron AS-16.000-18](https://octopart.com/as-16.000-18-raltron+electronics-973373)|
|1|4.7 uF electrolytic capacitor|C1|[Panasonic ECA-1HM4R7I](https://octopart.com/eca-1hm4r7i-panasonic-39478610)|
|2|100 nF ceramic disk capacitor|C2, C3|[Kemet C315C104M5U5TA](https://octopart.com/c315c104m5u5ta-kemet-83288)|
|2|22 pF ceramic disk capacitor|C4, C5|[Kemet C317C220J1G5TA](https://octopart.com/c317c220j1g5ta-kemet-1747641)|
|1|10 kΩ resistor|R4|[Multicomp MF25 10k](https://octopart.com/mf25+10k-multicomp-2697429)|
|2|68 Ω resistor|R2, R3|[Multicomp MF25 68R](https://octopart.com/mf25+68r-multicomp-5364489)|
|4|1.5 kΩ resistor|R1, R5, R6, R7|[Multicomp MF25 1k5](https://octopart.com/mf25+1k5-multicomp-5372506)|
|3|5mm LED (for the lock indicators)|LED1, LED2, LED3|[Vishay TLHG5400](https://octopart.com/tlhg5400-vishay-39403037)|
|2|3.6 V zener diode (DO-35 BZX55C3V6)|D1, D2|[ON Semiconductor BZX85C3V6](https://octopart.com/bzx85c3v6-on+semiconductor-84409073)|
|105|universal switching diode (DO-35 1N4148)|D3-D107|[ON Semiconductor 1N4148](https://octopart.com/1n4148-on+semiconductor-6807167)|

#### Some pictures of the first finished PCB
[![](https://i.imgur.com/3325BHBm.jpg)](https://i.imgur.com/3325BHB.jpg) [![](https://i.imgur.com/cYwRUWXm.jpg)](https://i.imgur.com/cYwRUWX.jpg)
[![](https://i.imgur.com/b2IuvLgm.jpg)](https://i.imgur.com/b2IuvLg.jpg) [![](https://i.imgur.com/vxiDwE3m.jpg)](https://i.imgur.com/vxiDwE3.jpg)
[![](https://i.imgur.com/lfABr6am.jpg)](https://i.imgur.com/lfABr6a.jpg) [![](https://i.imgur.com/BY7TV2wm.jpg)](https://i.imgur.com/BY7TV2w.jpg)

---
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
