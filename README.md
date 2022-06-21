# KODA_SHOPLIGHT_IR
IR CODES for the Koda 46" LED Linkable Shop Light Remote
For use in Arduino based IR Automation.

Derived using IR Receiver Diode - TSOP38238 https://learn.sparkfun.com/tutorials/ir-control-kit-hookup-guide
http://www.sparkfun.com/datasheets/Sensors/Infrared/tsop382.pdf

And the IR Remote Library
https://github.com/shirriff/Arduino-IRremote/

Extracted Codes

| Remote Control Function  | IR CODE | RAW IR |
| ------------- | ------------- |  ------------- |
| Power Button On  | 0x 7E7EA05F  | Raw: (71) 9120, -4480, 604, -560, 576, -1664, 608, -1684, 580, -1688, 584, -1684, 576, -1692, 584, -1680, 580, -560, 576, -560, 580, -1684, 576, -1692, 580, -1688, 576, -1692, 580, -1684, 580, -1688, 572, -564, 572, -1696, 580, -556, 580, -1684, 576, -560, 580, -556, 580, -556, 580, -556, 580, -556, 580, -556, 580, -1688, 576, -560, 576, -1692, 580, -1684, 580, -1688, 584, -1684, 580, -1688, 572, -35176, 9124, -2236, 604, 
Raw: (71) 9120, -4508, 576, -532, 604, -1664, 608, -1688, 576, -1664, 608, -1684, 580, -1660, 612, -1684, 576, -560, 576, -560, 580, -1660, 612, -1680, 580, -1688, 576, -1664, 608, -1688, 576, -1664, 608, -552, 584, -528, 608, -528, 608, -1660, 604, -532, 604, -532, 604, -532, 604, -556, 584, -552, 584, -1684, 576, -1664, 608, -528, 608, -1660, 604, -1688, 584, -1656, 608, -1688, 572, -1692, 584, -35164, 9120, -2240, 600, 
Raw: (71) 9124, -4476, 604, -560, 576, -1692, 584, -1684, 576, -1692, 580, -1684, 580, -1688, 584, -1684, 576, -560, 580, -556, 576, -1692, 584, -1680, 580, -1688, 584, -1684, 580, -1688, 572, -1692, 580, -556, 580, -1688, 576, -560, 576, -1692, 580, -556, 580, -556, 580, -556, 584, -552, 584, -552, 584, -552, 584, -1680, 580, -560, 576, -1688, 576, -1692, 580, -1688, 572, -1692, 584, -1684, 576, -35168, 9124, -2240, 600, 
Raw: (71) 9128, -4472, 612, -552, 584, -1684, 576, -1692, 584, -1680, 580, -1688, 576, -1692, 580, -1688, 572, -564, 576, -560, 576, -1688, 584, -1684, 576, -1692, 580, -1688, 576, -1688, 584, -1684, 580, -556, 580, -556, 580, -556, 580, -1688, 576, -560, 572, -564, 576, -560, 576, -560, 576, -560, 576, -1692, 580, -1684, 580, -556, 580, -1688, 584, -1684, 580, -1684, 576, -1692, 580, -1688, 576, -35164, 9116, -2244, 608, |
| Power Button Off | 0x 7E7E20DF | |
| Sleep Button | 0x 7E7E0CF3 | |
| Minimum Brightness | 0x 7E7EB847 | |
| Decrease Brightness | 0x 7E7ED827 | |
| Increase Brightness | 0x 7E7E58A7 | |
| Maximum Brightness | 0x 7E7E38C7 | |
| Disable Brightness Dimmer Timer | 0x 7E7EB04F | |
| Enable 5 Minute Brightness Dimmer Timer | 0x 7E7E30CF | |
| Enable 10 Minute Brightness Dimmer Timer | 0x 7E7E708F | |
| Enable 30 Minute Brightness Dimmer Timer | 0x 7E7EF00F | |
| Disable Auto Off Timer | 0x 7E7E8877 | |
| Enable 5 Minute Auto Off Timer | 0x 7E7E08F7 | |
| Enable 10 Minute Auto Off Timer | 0x 7E7E48B7 | |
| Enable 30 Minute Auto Off Timer | 0x 7E7EC837 | |
| Disable Ambient Light Sensor | 0x 7E7EA857 | |
| Overcast | 0x 7E7E28D7 | |
| Dusk | 0x 7E7E6897 | |
| Night | 0x 7E7EE817 | |
| Set Distance Sensor Very Near | 0x 7E7E906F | |
| Set Distance Sensor Near | 0x 7E7E10EF | |
| Set Distance Sensor Mid-Range | 0x 7E7E50AF | |
| Set Distance Sensor Far | 0x 7E7ED02F | |


