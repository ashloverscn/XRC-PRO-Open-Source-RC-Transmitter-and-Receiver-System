# XRC-PRO-Open-Source-RC-Transmitter-and-Receiver-System
BY DIY TECHOS MR AHSAN BILAL

XRC PRO is a powerful, open-source RC transmitter and receiver system using STM32 and NRF24L01. It features real-time control.

Links to original Source:

https://www.instructables.com/XRC-PRO-Open-Source-RC-8CH-Transmitter-and-Receive/

https://projecthub.arduino.cc/diytechos786/xrc-pro-open-source-rc-transmitter-and-receiver-system-with-stm32-nrf24l01-c769f3

https://hackaday.io/page/399158-xrc-pro-open-source-rc-transmitter-and-receiver-system-with-stm32nrf24l01

https://www.pcbway.com/project/shareproject/XRC_PRO_Open_Source_RC_Transmitter_and_Receiver_System_bd9ee6c2.html

https://maker.pro/arm-mbed/projects/xrc-pro-open-source-rc-8ch-transmitter-and-receiver-with-stm32


Description
XRC PRO: Open-Source RC Transmitter and Receiver System
Overview
The XRC PRO is an advanced, open-source RC transmitter and receiver system designed to offer professional-level performance in a compact and customizable package. Built around the STM32F103C8T6 microcontroller and the NRF24L01 wireless transceiver module, the XRC PRO provides precise, real-time control for various RC applications like drones, cars, and boats. With a compact design, robust functionality, and user-friendly interface, the XRC PRO is an ideal tool for both hobbyists and professionals.

Links to Youtube Video:

https://youtu.be/UNfOPE7gjmE?si=JsrTXxZbttpd0SDJ

Key Features:
OLED Display: Shows real-time signal strength, settings, battery percentage, and control data for easy monitoring.
Trim Buttons & Rotary Encoder: Provides fine-tuned control and simple menu navigation, enhancing usability.
Multi-Menus: Features an intuitive menu system for adjusting channel settings, polarity, and output modes.
PPM & SBUS Outputs: Offers versatile output options, supporting a range of RC receivers for greater functionality.
NRF24L01 Power Control: Includes adjustable signal strength settings, allowing for both short- and long-range control.
Stick Calibration: Enables real-time stick calibration with visual feedback on the OLED display for precise adjustments.
Compact Receivers: Offers two efficient receiver options for 8-channel PWM+PPM and PPM+SBUS outputs, designed for optimal performance.
Throttle Mode: Allows selection between left or right throttle hand mode to suit user preferences.
PC Simulator Compatibility: Supports computer-based simulators through PPM output, with an option to toggle PPM output on or off.
Express ELRS Integration: Compatible with ELRS modules via PPM output when used with an ELRS adapter.
Buzzer On/Off Mode: Enables users to easily toggle the buzzer for audio feedback during operation.
Adjustable Setting Unit: Allows customization of measurement units (e.g., degrees, percentages) based on user preference.
Battery Voltage Calibration: Calibrate battery voltage display for accurate percentage readings, ensuring reliable battery monitoring.
Reset to Default Settings: Provides an option to restore all settings to default quickly for easy setup and troubleshooting.


Tech Specs
Microcontroller: STM32F103C8T6 ARM® Cortex®-M3

ARM® Cortex®-M3 core up to 72 MHz
20KB onboard SRAM
64KB Flash memory
Wireless Module: NRF24L01 GT24 Mini

Operates on 2.4 GHz ISM band
High data rate up to 2 Mbps
Supports multiple data pipes for communication
Display: 0.96" OLED

Displays signal strength, battery percentage, and control data
Power: AMS117 3.3V Regulator

Input voltage range from 7.4V to 12V (supports 2S to 3S LiPo batteries)
Weight: 200g (excluding battery)

Dimensions: 160 mm x 120 mm x 40 mm (excluding antenna)

Enclosure: DJI Phantom 2 Remote (customizable based on user preference; Arduino joysticks can be used as an alternative)



Transmitter Components
1.STM32F103C8T6: ARM microcontroller, desoldered from development board and soldered to transmitter PCB – Quantity: 1

Click to Buy: https://bit.ly/3ODReqC

2.NRF24L01 GT24 Mini: Wireless Transceiver Module – Quantity: 1

Click to Buy: https://bit.ly/3HTMQA0

2.E11 Rotary Encoder (ENC): Rotary encoder for menu navigation – Quantity: 1

Click to Buy: https://bit.ly/3UDggKq

3.SMD 8MHz Crystal (3225): Oscillator for STM32 – Quantity: 1

Click to Buy: https://shorturl.at/Ym75q

4.FC-135 32.768kHz Crystal: RTC crystal – Quantity: 1

Click to Buy: https://shorturl.at/v2CL1

5.CH340C SMD: USB to Serial Converter – Quantity: 1

Click to Buy: https://shorturl.at/4vJuk

6.Y1 (8050) NPN Transistor: General-purpose transistor – Quantity: 2

Click to Buy: https://n9.cl/b6pnc

7.1AM (3904) NPN Transistor: General-purpose transistor – Quantity: 1

Click to Buy: https://shorturl.at/Fs6E6

8.0.96" OLED Display: For displaying transmitter status and menu – Quantity: 1

Click to Buy: https://bit.ly/49arquy

9.10k Ohm Resistor (SMD): Resistor for various circuits – Quantity: 4

Click to Buy: https://bit.ly/3SAMR0D

10.1k Ohm Resistor (SMD): Resistor for various circuits – Quantity: 4

Click to Buy: https://bit.ly/3SAMR0D

11.100nF Capacitor (SMD): Signal filtering capacitor – Quantity: 20

Click to Buy: https://bit.ly/3ODT22S

12.Buzzer: Audio feedback for transmitter alerts – Quantity: 1

Click to Buy: https://bit.ly/3uru93D

13.AMS117 (3.3V Voltage Regulator): Provides 3.3V to components – Quantity: 1

Click to Buy: https://bit.ly/497yk3N

14.10uF Capacitor: Power stabilization and filtering – Quantity: 2

Click to Buy: https://bit.ly/3SzbI4Y

15.Male Headers: Connector for modules/components – Quantity: 30

Click to Buy: https://bit.ly/3uxOzrJ

16.DJI Phantom 2 Remote: Used as the transmitter enclosure; alternatives include any compatible remote/joystick.



Receiver Components
Receiver (PWM+PPM)
1.STM32F103C8T6: ARM microcontroller, desoldered from development board and soldered to receiver PCB – Quantity: 1

Click to Buy: https://bit.ly/3ODReqC

2.NRF24L01 GT24 Mini: Wireless Transceiver Module – Quantity: 1

Click to Buy: https://bit.ly/3HTMQA0

3.SMD 8MHz Crystal (3225): Oscillator for STM32 – Quantity: 1

Click to Buy: https://shorturl.at/Ym75q

4.1AM (3904) NPN Transistor: General-purpose transistor – Quantity: 1

Click to Buy: https://shorturl.at/Fs6E6

5.AMS117 (3.3V Voltage Regulator): Provides 3.3V to components – Quantity: 1

Click to Buy: https://shorturl.at/q2WBb

6.10uF Capacitor: Power stabilization and filtering – Quantity: 2

Click to Buy: https://bit.ly/3SzbI4Y

7.100nF Capacitor (SMD): Signal filtering capacitor – Quantity: 4

Click to Buy: https://bit.ly/3ODT22S

8.Male Headers: Connector for modules/components – Quantity: 30

Click to Buy: https://bit.ly/3uxOzrJ



Receiver (PPM+SBUS)
1.STM32F103C8T6: ARM microcontroller, desoldered from development board and soldered to receiver PCB – Quantity: 1

Click to Buy: https://bit.ly/3ODReqC

2.NRF24L01 GT24 Mini: Wireless Transceiver Module – Quantity: 1

Click to Buy: https://bit.ly/3HTMQA0

3.SMD 8MHz Crystal (3225): Oscillator for STM32 – Quantity: 1

Click to Buy: https://shorturl.at/Ym75q

4.1AM (3904) NPN Transistor: General-purpose transistor – Quantity: 1

Click to Buy: https://shorturl.at/Fs6E6

5.AMS117 (3.3V Voltage Regulator): Provides 3.3V to components – Quantity: 1

Click to Buy: https://shorturl.at/q2WBb

6.10uF Capacitor: Power stabilization and filtering – Quantity: 2

Click to Buy: https://bit.ly/3SzbI4Y

7.100nF Capacitor (SMD): Signal filtering capacitor – Quantity: 4

Click to Buy: https://bit.ly/3ODT22S

8.Male Headers: Connector for modules/components – Quantity: 30

Click to Buy: https://bit.ly/3uxOzrJ



Schematic and PCB Layout
The XRC PRO has multiple PCBs and it consists of three main PCBs: the Transmitter PCB, the 8-channel PWM+PPM Receiver PCB, and the PPM+SBUS Receiver PCB. Each PCB was carefully designed for space efficiency and optimal performance.



Transmitter PCBs
The Transmitter PCB is built around the STM32F103C8T6, NRF24L01 module, OLED display, and various input buttons (trim, menu, encoder). The schematic includes connections for power management (5v to 3.3v), data lines for the OLED, and button inputs for settings navigation etc.



Schematic and PCB Layout

https://www.elecrow.com/media/qb/tmp/common/image/2024/10/A_TRANSMITTER_154568540167110da1eb55f.png

Visual and Physical Connections
I’ve designed a detailed, color-coded connection schematic for all inputs and outputs, making it easy for anyone to assemble the XRC PRO transmitter and receivers. Additionally, I’ve included high-quality these images in PDF format, which you can download below.

Transmitter


https://www.elecrow.com/media/qb/tmp/common/image/2024/10/Screenshot_2024-10-12_130717_67499206670a33be9980b.png

Receiver(PWM+PPM)

https://www.elecrow.com/media/qb/tmp/common/image/2024/10/Screenshot_2024-10-12_130854_716421166670a33d0713d6.png

Receiver(PPM+SBUS)

https://www.elecrow.com/media/qb/tmp/common/image/2024/10/Screenshot_2024-10-12_130955_1957835085670a33ec96f70.png
