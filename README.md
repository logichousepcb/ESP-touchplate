# ESP-touchplate

This is a small low cost device I created that you can plug a Wemos D1 mini into.  There are 2 buttons using TTP223 boards and an LCD to display status (0.96 OLED)

I have the .STL file to 3D print an enclosure that fits in a decora switch plate cover.  The newest revision 2 fits better and has screw mounts.

ESPHome example YAML is included but I do plan to create MQTT control via arduino sketch in the near future.

If you want some of these boards, contact me for a good deal or the gerber.  This project is very inexpensive and the parts list in minimal.
1 x D1 Mini
2 x TTP223 Module Capacitive Touch Switch 
1 x I2C 128X64 OLED Display Module 
1 x 3d printed faceplate, although i started using my own 3d printed PCBWay can print then cheap and they come out great
2 x M2x6mm Hex Drive Head Cap Self Tapping Drilling Screws 
1 x 2.54mm PCB Screw Terminal Block (for 5v +/- or solder the wires directly, you can also power via the D1 USB)

** I have a new version in the works that will use passive POE and an RJ45 connector to power

![GitHub Logo](https://github.com/logichousepcb/ESP-touchplate/blob/main/esptouchplate.JPG)

