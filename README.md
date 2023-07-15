# Teensy-Telnet-Server

This is the basis of a Telnet server that I found here: https://gist.github.com/atomsfat/1813823

Originally written for the Arduino with the ethernet shield, I've modified it to work on the Teensy 4.1 using QNEEthern from https://github.com/ssilverman/QNEthernet.  This could be modified to work with the NativeEthernet library by making a few simple changes.

As written, this code lets you Telnet into your Teensy and provides a simple set of commands to perform A/D, D/A functions, and to set pin modes.  This functionality can be modified to suit your particular needs.  I plan on using this for remote access to other serial devices and function as a terminal-server.

This requires a Teensy 4.1 with its optional ethernet module to function.
