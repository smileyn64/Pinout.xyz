<!--
---
name: IO Pi Plus
class: board
type: io
formfactor: HAT
manufacturer: AB Electronics
description: Carte d'expansion 32 Canaux Digitaux
url: https://www.abelectronics.co.uk/p/54/IO-Pi-Plus
github: https://github.com/abelectronicsuk
buy: https://www.abelectronics.co.uk/p/54/IO-Pi-Plus
image: 'ab-io-pi-plus.png'
pincount: 40
eeprom: no
power:
  '1':
  '2':
ground:
  '6':
  '9':
  '14':
  '20':
  '25':
  '30':
  '34':
  '39':
pin:
  '3':
    mode: i2c
  '5':
    mode: i2c
i2c:
  '0x20':
    name: MCP23017
    device: MCP23017
  '0x21':
    name: MCP23017
    device: MCP23017
-->
#IO Pi Plus

Le **IO Pi Plus** de **AB Electronics** est une carte chapeau d'extension à 32 canaux digitaux conçu pour fonctionner avec le Raspberry Pi. Le **IO Pi Plus** est basé sur une micro-puce **MCP23017 16-bit I/O expander** de **Microchip Technologies Inc**.

Deux micro-puces **MCP23017** sont présente sur la carte chapeau permettant de rajouter jusqu'à 32 entrée ou sorties digitales au Raspberry Pi. Le **IO Pi Plus** est alimenté par le Raspberry Pi au travers du port GPIO et permet de connecter d'autres carte chapeau.

##Caractéristiques

-  32 Entrées/sorties Digitales
-  Control via the Raspberry Pi I2C port
-  Stack up to 4 IO Pi boards on a single Raspberry Pi
-  Jumper selectable I2C addresses
-  External 5V Input with isolation jumper
-  Based on the MCP23017 from Microchip Technologies Inc
-  Configurable interrupt output pins - Configurable as active-high, active-low or open-drain
-  INTA and INTB can be configured to operate independently or together
-  Configurable interrupt source  - Interrupt-on-change from configured register defaults  or pin changes
-  Polarity Inversion register to configure the polarity of the input port data

Arduino, C, Node.js, Windows 10 IOT, Python 2 and Python 3 libraries are available on GitHub.
