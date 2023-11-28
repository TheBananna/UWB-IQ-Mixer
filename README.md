# UWB-IQ-Mixer
 
This is an ultra wideband (23.5-6000 MHZ) active mixer design I'm working on for future integration into a wideband SDR design. It utilizes two PLLs driven by DACs to be able to precisely phase control the output of the PLLs that are then used as LOs for the two diode ring mixers. Such precise phase control should be able to achieve excellent sideband rejection. Because the PLLs can coarsely control their power output I'm waiting to see how bad the amplitude balance will be before I add LO bias as that issue can be corrected in gateware with minimal performance degredation with a self calibration. I use a K26 SOM to drive the 500 MSPS dual DAC because it offers an extrordinary price to performance ratio across multiple projects as you only have to pay for the connectors each board uses.

At the moment I've finished the schematic and am, hopefully, about halfway through layout. 
