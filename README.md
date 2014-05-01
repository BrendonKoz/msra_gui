msra_gui
========

This small AutoIT Script creates a GUI window to assist with the use of Microsoft's own Remote Assistance tool. The tool, as far as I am aware, has no GUI to initiate a help request from the side of technical support - only from those requesting help, which is a bit more cumbersome. When using a command line switch, a technical support person can initiate the help request in order to view, and remote control a PC on the network.

This tool (very quickly) queries ActiveDirectory for all computers, populating an auto-fill dropdown selection box. A technician may manually type in the PC name (helpful if not yet listed in ActiveDirectory), or choose from the list and then click the super large button, "Remote Assist" - or leave the field blank and press the button, then select from their list of PCs in their remote session history.

It's quite a bit easier than fumbling through the command line, and a little bit faster for most.

============

As stated, this script was created in the AutoIT scripting language. To compile, one must use the AutoIT compiler which is freely downloaded from:
http://autoitscript.com/
