Arduino-CC2500-Library
======================

This library is used to connect CC2500 RF Module (Texas Instruments) with Arduino.
This library is tested on Arduino UNO. 
Packet Transmission is used (Variable Packet Length).


Arduino UNO Pin Configration With CC2500 Module


Arduino Pin (4)         -> CC2500 Pin (6)  [GDO0]

Arduino Pin (13) [SCK]  -> CC2500 Pin (1)  [SCLK]

Arduino Pin (12) [MISO] -> CC2500 Pin (20) [SI]

Arduino Pin (11) [MOSI] -> CC2500 Pin (2)  [SO]

Arduino Pin (10) [SS]   -> CC2500 Pin (7)  [CSn]


Arduino Pin (3.3V)      -> CC2500 [VCC]

Arduino Pin (GND)       -> CC2500 [GND]



CC2500 Configuration Specifications
------------------------------------------------------------------------------------

Sync word qualifier mode = 30/32 sync word bits detected

CRC autoflush = false

Channel spacing = 199.951172

Data format = Normal mode

Data rate = 2.39897

RX filter BW = 203.125000

Preamble count = 4

Whitening = false

Address config = No address check

Carrier frequency = 2432.999908

Device address = 0

TX power = 0

Manchester enable = false

CRC enable = true

Deviation = 38.085938

Packet length mode = Variable packet length mode. Packet length configured by the first byte after sync word

Packet length = 255

Modulation format = 2-FSK

Base frequency = 2432.999908

Modulated = true

Channel number = 0
