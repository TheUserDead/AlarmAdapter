# AlarmAdapter

This is a wireless adapter device & software for security centrals whitch does not have wireless sensors.
So with it you can buy and use 433 MHZ wireless sensor with your security system in your private area.
Principle is very easy:
All recorded wireless sensors are listening by this adapter. When signal received, adapter enables wired signal on terminal ports in defined area like it's has wired connected directly.

HHow to use. After build & program device. (Now only with serial monitor connected! Use Smartphone OTG and terminal or PC)
Your old (not too) security system has 6/8/16 wired sensing contacts based on NC \ NO input state.
-You just connect adapter to these inputs & install device near with antenna
-Connect terminal and enter adapter in program mode use "prog" command.
-Uses short help, turn on the wireless sensor and let it work so that the receiver of the adapter reads the serial number of the sensor and stores it in memory.
-Use "work" command, device print codes of sensors and save it in EEPROM
-When any signal received of registered sensors it's made signal on terminal contacts.

ToDo list:
1) Made base program)
2) Store and clean procedures of serials
3) Navigate in codes memory. Add\remove\re-write cells.
4) Setup NC or NO mode for varoups centrals
5) ???


IT'S BASE REPOSITORY FOR CONTINOUS WORK
