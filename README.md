# KODA_SHOPLIGHT_IR
IR CODES for the Koda 46" LED Linkable Shop Light Remote
For use in Arduino based IR Automation.

Derived using IR Receiver Diode - TSOP38238 https://learn.sparkfun.com/tutorials/ir-control-kit-hookup-guide
http://www.sparkfun.com/datasheets/Sensors/Infrared/tsop382.pdf

And Raspberry Pi with LIRC:
https://shallowsky.com/blog/hardware/raspberry-pi-ir-remote.html

https://osoyoo.com/2016/12/15/raspberrypi-ir-remote/

http://alexba.in/blog/2013/01/06/setting-up-lirc-on-the-raspberrypi/



------------------------------

# Legacy [Did not work]

Using the IR Remote Library
https://github.com/shirriff/Arduino-IRremote/

RAW IR Codes captured using
https://www.analysir.com/blog/2014/03/19/air-conditioners-problems-recording-long-infrared-remote-control-signals-arduino/
https://www.analysir.com/blog/wp-content/uploads/2014/03/Arduino_Record_Long_AirConditioner_Infrared_Signals_10.txt


Extracted Codes

| Remote Control Function  | IR CODE | RAW IR 1 | RAW IR 2 | RAW IR 3 | RAW IR 4 | 
| ------------- | ------------- |  ------------- | ------------- | ------------- | ------------- |
| Power Button On  | 0x 7E7EA05F  | Raw: (71) 9120, -4480, 604, -560, 576, -1664, 608, -1684, 580, -1688, 584, -1684, 576, -1692, 584, -1680, 580, -560, 576, -560, 580, -1684, 576, -1692, 580, -1688, 576, -1692, 580, -1684, 580, -1688, 572, -564, 572, -1696, 580, -556, 580, -1684, 576, -560, 580, -556, 580, -556, 580, -556, 580, -556, 580, -556, 580, -1688, 576, -560, 576, -1692, 580, -1684, 580, -1688, 584, -1684, 580, -1688, 572, -35176, 9124, -2236, 604, | Raw: (71) 9120, -4508, 576, -532, 604, -1664, 608, -1688, 576, -1664, 608, -1684, 580, -1660, 612, -1684, 576, -560, 576, -560, 580, -1660, 612, -1680, 580, -1688, 576, -1664, 608, -1688, 576, -1664, 608, -552, 584, -528, 608, -528, 608, -1660, 604, -532, 604, -532, 604, -532, 604, -556, 584, -552, 584, -1684, 576, -1664, 608, -528, 608, -1660, 604, -1688, 584, -1656, 608, -1688, 572, -1692, 584, -35164, 9120, -2240, 600, | Raw: (71) 9124, -4476, 604, -560, 576, -1692, 584, -1684, 576, -1692, 580, -1684, 580, -1688, 584, -1684, 576, -560, 580, -556, 576, -1692, 584, -1680, 580, -1688, 584, -1684, 580, -1688, 572, -1692, 580, -556, 580, -1688, 576, -560, 576, -1692, 580, -556, 580, -556, 580, -556, 584, -552, 584, -552, 584, -552, 584, -1680, 580, -560, 576, -1688, 576, -1692, 580, -1688, 572, -1692, 584, -1684, 576, -35168, 9124, -2240, 600, | Raw: (71) 9128, -4472, 612, -552, 584, -1684, 576, -1692, 584, -1680, 580, -1688, 576, -1692, 580, -1688, 572, -564, 576, -560, 576, -1688, 584, -1684, 576, -1692, 580, -1688, 576, -1688, 584, -1684, 580, -556, 580, -556, 580, -556, 580, -1688, 576, -560, 572, -564, 576, -560, 576, -560, 576, -560, 576, -1692, 580, -1684, 580, -556, 580, -1688, 584, -1684, 580, -1684, 576, -1692, 580, -1688, 576, -35164, 9116, -2244, 608, |
| Power Button Off | 0x 7E7E20DF |  Raw: (71) 9120, -4480, 604, -560, 576, -1664, 608, -1684, 580, -1688, 584, -1684, 576, -1692, 584, -1680, 580, -560, 576, -560, 580, -1684, 576, -1692, 580, -1688, 576, -1692, 580, -1684, 580, -1688, 572, -564, 572, -1696, 580, -556, 580, -1684, 576, -560, 580, -556, 580, -556, 580, -556, 580, -556, 580, -556, 580, -1688, 576, -560, 576, -1692, 580, -1684, 580, -1688, 584, -1684, 580, -1688, 572, -35176, 9124, -2236, 604, | Raw: (71) 9120, -4508, 576, -532, 604, -1664, 608, -1688, 576, -1664, 608, -1684, 580, -1660, 612, -1684, 576, -560, 576, -560, 580, -1660, 612, -1680, 580, -1688, 576, -1664, 608, -1688, 576, -1664, 608, -552, 584, -528, 608, -528, 608, -1660, 604, -532, 604, -532, 604, -532, 604, -556, 584, -552, 584, -1684, 576, -1664, 608, -528, 608, -1660, 604, -1688, 584, -1656, 608, -1688, 572, -1692, 584, -35164, 9120, -2240, 600, | For IR Scope: +9050 -4450 +600 -550 +550 -1650 +600 -1650 +600 -1650 +600 -1650 +600 -1650 +600 -1650 +550 -600 +550 -550 +550 -1700 +550 -1700 +550 -1700 +550 -1700 +550 -1650 +600 -1650 +600 -550 +550 -550 +600 -550 +550 -1700 +550 -550 +600 -550 +550 -550 +600 -550 +550 -550 +600 -1650 +600 -1650 +550 -600 +550 -1650 +600 -1650 +600 -1650 +600 -1650 +600 -1650 +550 For Arduino sketch: unsigned int raw[68] = {9050,4450,600,550,550,1650,600,1650,600,1650,600,1650,600,1650,600,1650,550,600,550,550,550,1700,550,1700,550,1700,550,1700,550,1650,600,1650,600,550,550,550,600,550,550,1700,550,550,600,550,550,550,600,550,550,550,600,1650,600,1650,550,600,550,1650,600,1650,600,1650,600,1650,600,1650,550,};irsend.sendRaw(raw,68,38); | For IR Scope:  +9050 -4400 +600 -550 +600 -1650 +600 -1650 +550 -1700 +550 -1700 +550 -1700 +550 -1700 +550 -550 +600 -550 +550 -1700 +550 -1650 +600 -1650 +600 -1650 +600 -1650 +600 -1650 +550 -550 +600 -1650 +600 -550 +550 -1700 +550 -550 +600 -550 +550 -550 +600 -550 +550 -550 +600 -550 +550 -1700 +550 -550 +600 -1650 +550 -1700 +550 -1700 +550 -1700 +550 -1700 +550  For Arduino sketch:  unsigned int raw[68] = {9050,4400,600,550,600,1650,600,1650,550,1700,550,1700,550,1700,550,1700,550,550,600,550,550,1700,550,1650,600,1650,600,1650,600,1650,600,1650,550,550,600,1650,600,550,550,1700,550,550,600,550,550,550,600,550,550,550,600,550,550,1700,550,550,600,1650,550,1700,550,1700,550,1700,550,1700,550,};irsend.sendRaw(raw,68,38); |
| Sleep Button | 0x 7E7E0CF3 | Raw: (71) 9140, -4464, 624, -540, 596, -1672, 592, -1672, 600, -1668, 592, -1648, 624, -1644, 616, -1652, 620, -544, 592, -544, 592, -1676, 596, -1672, 588, -1680, 592, -1676, 596, -1644, 620, -1648, 620, -540, 596, -540, 600, -540, 592, -544, 592, -544, 596, -1668, 600, -1668, 596, -540, 596, -540, 596, -1672, 596, -1672, 592, -1676, 596, -1644, 616, -544, 592, -548, 588, -1676, 596, -1672, 600, -35148, 9140, -2224, 624, | Raw: (71) 9148, -4456, 620, -540, 596, -1672, 600, -1640, 620, -1648, 624, -1644, 620, -1648, 620, -1648, 624, -540, 600, -536, 596, -1672, 592, -1672, 600, -1644, 624, -1644, 620, -1648, 620, -1644, 620, -544, 600, -536, 600, -536, 600, -540, 596, -536, 600, -1668, 592, -1676, 596, -540, 596, -540, 596, -1672, 600, -1668, 592, -1648, 624, -1644, 616, -544, 592, -548, 588, -1676, 596, -1672, 600, -35144, 9140, -2224, 624, | Raw: (71) 9148, -4456, 620, -544, 592, -1676, 596, -1668, 604, -1640, 620, -1648, 624, -1644, 628, -1636, 624, -540, 596, -540, 596, -1672, 600, -1668, 604, -1636, 624, -1644, 628, -1640, 620, -1648, 624, -540, 596, -540, 596, -540, 596, -540, 592, -544, 592, -1672, 600, -1668, 604, -532, 604, -536, 600, -1664, 596, -1672, 600, -1668, 592, -1648, 624, -540, 596, -540, 596, -1672, 600, -1664, 596, -35152, 9140, -2224, 624, | Raw: (71) 9156, -4448, 628, -536, 600, -1668, 604, -1664, 596, -1644, 628, -1640, 632, -1636, 624, -1640, 632, -532, 600, -540, 596, -1668, 604, -1664, 596, -1672, 600, -1668, 604, -1636, 624, -1644, 628, -536, 600, -536, 600, -536, 596, -540, 596, -540, 596, -1672, 600, -1664, 596, -544, 592, -544, 604, -1660, 600, -1668, 604, -1636, 624, -1644, 628, -536, 596, -540, 596, -1672, 600, -1664, 596, -35148, 9140, -2224, 628, |
| Minimum Brightness | 0x 7E7EB847 | | | | |
| Decrease Brightness | 0x 7E7ED827 | | | | |
| Increase Brightness | 0x 7E7E58A7 | | | | |
| Maximum Brightness | 0x 7E7E38C7 | | | | |
| Disable Brightness Dimmer Timer | 0x 7E7EB04F | | | | |
| Enable 5 Minute Brightness Dimmer Timer | 0x 7E7E30CF | | | | |
| Enable 10 Minute Brightness Dimmer Timer | 0x 7E7E708F | | | | |
| Enable 30 Minute Brightness Dimmer Timer | 0x 7E7EF00F | | | | |
| Disable Auto Off Timer | 0x 7E7E8877 | | | | |
| Enable 5 Minute Auto Off Timer | 0x 7E7E08F7 | | | | |
| Enable 10 Minute Auto Off Timer | 0x 7E7E48B7 | | | | |
| Enable 30 Minute Auto Off Timer | 0x 7E7EC837 | | | | |
| Disable Ambient Light Sensor | 0x 7E7EA857 | | | | |
| Overcast | 0x 7E7E28D7 | | | | |
| Dusk | 0x 7E7E6897 | | | | |
| Night | 0x 7E7EE817 | | | | |
| Set Distance Sensor Very Near | 0x 7E7E906F | | | | |
| Set Distance Sensor Near | 0x 7E7E10EF | | | | |
| Set Distance Sensor Mid-Range | 0x 7E7E50AF | | | | |
| Set Distance Sensor Far | 0x 7E7ED02F | | | | |

