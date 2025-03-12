# zx-specdrum-re-created
Recreated and improved version of Currah Specdrum Interface for ZX Spectrum

Work on this was initiated because existing schema found on the internet is with errors.

# Version 1
First version is more or less a 1:1 copy of the original interface. With help I got the correct values and type for all the Capacitors. The only changes compared with original:
* PCB made more compact to fit into my ZX-Bus-Extender board, you can use a normal edge connecter if you prefer.
* Some components moved, all ICs now have the same orientation.
* Make sure all ICs have decoupling capacitors.
* Added a 3.5" mini-jack plug for audio out.

BOM:


## This is how version 1 turned out
| <!---> | <!---> |
| ------ | ------ |
|![image](https://github.com/user-attachments/assets/fb373861-e162-4ace-9c92-fd48a1fd69d2)|![image](https://github.com/user-attachments/assets/cfbf3ff1-081e-4513-9325-024fa989f5a1)|

And it sounds like this in action https://youtube.com/shorts/cKAM5VnGr6U?feature=share

# Version 2
This update fixes a few errors from the initial release and introduces an option for sound enhancement:

* bypassed the anti-aliasing filter and somewhat improved the bass response
* option to switch between original or improved output (using jumper)
* C7 - changed from Ceramic 1uF to Electrolytic 10uF

BOM (recommended order):
* 4 x 6,2K Resistor
* 2 x 10,0K Resistor
* 2 x 100K Resistor
* 1 x 390R Resistor
* 1 x 680R Resistor
* 1 x 390K Resistor

* 3 x 100nF - MLC Capacitor P2,54
* 1 x 1nF - Ceramic Capacitor P2,54

* 1 x 2,7nF - Ceramic Capacitor P2,54
* 1 x 2,2nF - Ceramic Capacitor P2,54
* 1 x 82pF - Ceramic NPO P5,08

* 3 x 1uF - Tantal P5,08
* 1 x 22uF - Electrolyte Capacitor P2,54
* 1 x 10uF - Electrolyte Capacitor P2,54

* 1 x 74LS32
* 1 x TL084
* 1 x ZN428E-8
* 3.5 mono jack [like this](https://elektronik-lavpris.dk/p136328/pj-211-35mm-mono-jack-chassis-med-afbryder-switch/)

The sound improvement modification was suggested by D.A. Wilson of Hideaway Studio and is used here with permission. You can read about the mod [here](https://spectrumcomputing.co.uk/forums/viewtopic.php?t=4845)
