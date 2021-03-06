<!--
---
name: Pi-LITE-r
class: board
type: led
formfactor: Custom
manufacturer: Ciseco
description: An 8 LED strip for the Raspberry Pi
url: http://www.averagemanvsraspberrypi.com/2014/04/how-to-use-pi-liter-from-ciseco.html
buy: http://cpc.farnell.com/wirelessthings/pi-liter/pi-lite-junior-led-io-board-for/dp/SC13293
image: 'pi-liter.png'
pincount: 26
eeprom: no
power: 3v3
pin:
  '7':
    name: LED1
    direction: output
    active: high
  '11':
    name: LED2
    direction: output
    active: high
  '12':
    name: LED4
    direction: output
    active: high
  '13':
    name: LED3
    direction: output
    active: high
  '15':
    name: LED5
    direction: output
    active: high
  '16':
    name: LED6
    direction: output
    active: high
  '18':
    name: LED7
    direction: output
    active: high
  '22':
    name: LED8
    direction: output
    active: high
-->
#Pi-LITE-r

The Pi-LITEr is a fully assembled add on board for the Raspberry Pi. It has 8 ultra-bright white LED's on a board which plugs directly onto the GPIO header. It can be used alongside other I/O projects to give status indication. Lighting all 8 LEDs consumes a tiny amount of current, less than a single standard LED (which is 20ma nominal vs 14.4ma for the Pi-LITEr).

Applications:

* I/O status indicator
* Bar graph
* Light chaser
* Activity indicator
* Lighting effects