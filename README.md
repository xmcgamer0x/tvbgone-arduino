# Arduino TV-B-Gone
I created this improved version of the TV-B-Gone for Arduino, since the one on the Internet is outdated (from 2010), 
only works for some AVRs (Atmega328P) and uses a poorly coded method to send IR signals. Also all IR codes are saved
in a RAW format (on/off pulses) which doesnt make it easy to add new codes.

WARNING! This project uses a modded version of the Arduino-IRremote library in order to work with the Attiny85
and to use more IR protocols. You find the modded version in my github page!

You can use the IRrecvDump project example from the library to dump codes from the remote.
I provide a modified version of the IRrecvDump which has some improvements like more remote types and better readability.

