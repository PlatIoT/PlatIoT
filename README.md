# PlatIoT

(c) 2016 Ed Estes, Chris Hodapp, Ryan Anderson

## Raspberry Pi UPS

### Existing projects

- [UPSPIco](https://www.modmypi.com/raspberry-pi/breakout-boards/pi-modules/ups-pico)
- [Pi UPS +](http://www.piups.net/)
- [MoPi](http://pi.gate.ac.uk/mopi)
    - Its control software is open source:
      [simbamon](https://github.com/hamishcunningham/pi-tronics/tree/master/simbamon),
      Simple Battery monitor daemon
- [SmartUPS](http://www.mindsensors.com/rpi/41-uninterruptible-power-supply-for-raspberry-pi)

### Parts to look at

- [AdaFruit charger](https://www.adafruit.com/product/390)
    - Based on [MCP73871](https://www.microchip.com/wwwproducts/en/MCP73871)
    - 1A max may be insufficient, however, this seems to do the pass-through charging that we'll need.
- [AdaFruit PowerBoost 1000 charger](https://www.adafruit.com/products/2465)
    - Based on MCP73871 and TI [TPS61090](http://www.ti.com/product/tps61090)
    - This handles more power than the one linked above due.
- [SparkFun Power Cell](https://www.sparkfun.com/products/11231)
    - Based on MCP73871 and TI TPS61200.
    - Less-capable, but has schematics available.

## Standards to take note of

- [HAT, Hardware Attached on Top](https://www.raspberrypi.org/blog/introducing-raspberry-pi-hats/)
    - [GitHub repo](https://github.com/raspberrypi/hats)
