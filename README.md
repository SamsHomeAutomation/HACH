# HACH
Home Automation Control Hardware

Introduction:
We are developing a Home Automation Control Hardware, which consists of a Control Module and Extension Modules that allow for the control of lighting and other equipment through ESPHome and Home Assistant.

Control Module:
The Control Module is the main component and includes an esp32 microcontroller, ethernet and RS485 ports, zero-cross detection, and i2c link ports with extender chips. It also has two programmable LEDs, two tactile switches, and a programming header. The board is powered by a 100-240VAC supply, while the link power to extension modules and all other board power is 3.3V. The RS485 port enables communication with modbus enabled equipment such as solar PV systems. The Control Module is designed to run ESPHome firmware.

SSR Output Module:
This module can be linked to the Control Module using an RJ45 patch lead and can be used to switch or dim mains voltage lamps up to 2 amps. All eight output channels are individually fused and controlled.

Switch Input Module:
The Switch Input Module is used to attach standard toggle light switches, retractive light switches, push buttons, and dry contacts volt-free contacts. All 16 inputs have hardware pullup and debounce, and each input has two screw terminals for common ground and input signal. The module can be linked to the Control Module using an RJ45 patch lead.

Switch & SSR Module:
This module is a combination of the SSR Output Module and the Switch Input Module, featuring 12 inputs and 4 outputs. It can be linked to the Control Module using an RJ45 patch lead.

4chPro Adapter:
The 4chPro Adapter allows the use of a Sonoff 4ch Pro as the Control Module, expanding its capabilities by adding the Switch Inputs Module, SSR Output Module, and/or the Switch and SSR Module. The adapter is soldered to the program port inside the Sonoff and provides an RJ45 link port.

Mounting:
All boards are designed to fit in Phoenix Contact UM 72 profile din rail mounts and can be mounted inside a control panel. The hardware is versatile and can be used for many tasks other than just lighting, such as heating controls.

Development:
Our hardware is still in the development stage, with PCBs currently being designed. We plan to produce some prototype boards for bench testing in early 2023, with small production runs for sale in the future.

Conclusion:
If you have any questions, comments, suggestions for improvement, or ideas for more modules, please feel free to create a discussion. We will try our hardest to answer everyone.

--UPDATE 22.01.2023--
The through hole version of the Switch Input module has been sent off to PCBWay to be printed. this will be tested within the next month.
This module is compatible with sonoff 4ch pro and other sonoff models with custom made link cable. The 4ch pro link modules have also been sent off to print.
The 4ch pro link module makes for a easy reliable connection to a sonoff 4ch pro by way of an rj45 connector. This is experimental and testing will be carried out within the next month.
All Gerber files for Switch Input Module through hole version are now available to use.
