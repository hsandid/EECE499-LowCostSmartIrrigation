# Components to Order for the Prototype

- LoRaWAN Gateway System, operating on EU868 ISM Band (2pc)
- LoRa Transceiver, UART Compatible & operating on EU868 ISM Band (3pc)
- 868MHz U.FL Antenna for the LoRa Transceiver (3pc)
- GSM Module, UART Compatible & operating on Lebanese 2G/GSM (i.e frequency 900MHz) (3pc)
- 900MHz U.FL Antenna for the GSM Module (3pc)
- 40 Pins Male Connector (3pc)
- 40 Pins Female Connector (3pc)

### (1) LoRaWAN Gateway Module

- Number of supported channels : Up-to 8 channels
- Frequency Supported : Should operate on the same ISM band as our selected LoRa transceiver, in this case ISM band EU868.

**OPTION 1** : Buy an additional Raspberry-Pi, and a PI-HAT LoRaWAN Gateway module (sold separately).
Proposed Model : Pi-Supply (868MHz Support) (https://uk.pi-supply.com/products/iot-lora-gateway-hat-for-raspberry-pi)

**OPTION 2 **: Buy a Fully Enclosed System, which includes a Raspberry-Pi board and a LoRaWAN Gateway module
Proposed Model : IMST (868 MHz Support) (https://shop.imst.de/wireless-modules/lora-products/36/lite-gateway-demonstration-platform-for-lora-technology). Requires additional accesories : Antenna (https://shop.imst.de/wireless-modules/accessories/19/sma-antenna-for-ic880a-spi-wsa01-im880b-and-lite-gateway) and Power Supply (https://shop.imst.de/wireless-modules/accessories/37/power-supply-unit-for-lite-gateway)


### (2) LoRa Transceiver

- Serial Interface Support : UART
- Frequency Supported : Should operate on the same ISM band as our selected LoRaWAN Gateway, in this case ISM band EU868.

Proposed Model : Digikey (868MHz Support) (https://www.digikey.com/product-detail/en/multi-tech-systems-inc/MTXDOT-EU1-A00-1/591-1292-ND/6237035). This module is compatible with an U.FL antenna, which must be bought separetely.

### (3) 868MHz U.FL Antenna for the LoRa Transceiver
- No specific request for this component.

### (4) GSM Module
- Serial Interface Support : UART
- Technology Support : E-GSM, which operates at 900MHz frequency in Lebanon

Proposed Model : Digikey (2G) (https://www.digikey.com/product-detail/en/nimbelink-llc/NL-SW-GPRS/1477-1003-ND/4573470) This module is compatible with an U.FL antenna, which must be bought separetely. Our antenna should support the 900MHz frequency, which is related to 2G/EDGE technology for data services.

### (5) 900MHz U.FL Antenna for the GSM Module 
- No specific request for this component.

### (6) 40 Pins Male Connector

- No specific request for this component.

### (7) 40 Pins Female Connector

- Should be compatible with the Raspberry-Pi's GPIO Interface