# Sandin Image Processor
Digital representation of Sandin Image Processor in Max/MSP

Watch the video "5 Minute Romp thru the IP" excerpt 3:52 min (1973) for inspiration.

Welcome to the wonderful world of patching. The digital Sandin Max/Msp/Jitter patch is inspired by the analog modular video synthesizer by physicist, artist, and educator Dan Sandin. This patch remakes the invention in a program that mimics modules and patch cables. It celebrates the freedom of the IP in terms of the intellectual property too which Sandin firmly believes should be shared with the public. To learn more history, visit the dossier.
https://docs.google.com/document/d/1lrOtApNmYl388JM3hzE5PaHV6QDmzjfDE9AeuO1j-TI/edit?usp=sharing

This project investigates the analog Sandin Image Processor 1971-73 using media archeology “zombie” art methodology to examine the concept of ‘obsolete’ or ‘dead’ media to find sustainable, socially equitable art and design solutions. Garnet Hertz and Jussi Parikka state zombie media “is concerned with media that is not only out of use, but resurrected to new uses, contexts and adaptations.”  The media archeological process of revivifying becomes a reclamation of epistemological space - a space and a place in which the gadget opens up and the way it works becomes familiar and allows the machine to become your toy, your game, your invention. The original-copy, old-new, average-deviant, analog-digital - these binary dialectics are artificial divisions in media archeology. Analog patches have evolved into programs called MaxMsp/Jitter. As a work in progress, opening the black box of image processing techniques through remaking the Sandin Image Processor opened the history of the development of computer vision. 

INSTALLATION 

The analog Sandin Image Processor was recreated using Max/MSP software https://cycling74.com/downloads (min. requirement Max 8). The free version will allow to run and modify the Sandin app but no changes will be saved. 

The following color codes are used for all the modules inputs and outputs: 

RED - video signal 
GREEN - oscillator signal (for automatically controlling knob values)
BLUE - second video signal for mixing 

VIDEO PLAYER, CAMERA and OSC will generate video signals. All other modules are effects, i.e. require a video ingal input. To see the image a video signal has to be connected to MONITOR. 

To connect modules together open the app, unulock it (padlock icon bottom left or CMD + E), click an output (bottom of the module) and drag the cord to an input (top of the module). An example configuration: CAMERA -> FUNCTION GENERATOR -> MONITOR. The modules can be chained to create more complicated array of effects. 
