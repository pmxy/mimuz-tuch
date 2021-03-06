# mi:muz:tuch (MIDI Controller with flexible touch keys)

![mi:muz:tuch](device.png)

mi:muz:tuch is a USB MIDI controller with capacitive touch sensor.
It has now two indivisual versions, AVR or STM32.

Both version has same features:

- 6ch capacitive touch sensors with LEDs
- USB MIDI (USB MIDI Class compliant device mode)
- Calibration switch for manual calibration in anytime
- [Web MIDI Configurator](http://mz4u.net/tuch/)

# AVR Version (ATtiny44 16Mhz with ATmega8A 8Mhz)

AVR version of mi:muz:tuch (v0.1x) is based mi:muz:expr#2 for 'Hybrid MIDI feature, It can be able to connect to PC's USB Port using V-USB or mi:muz:mstr (I2C master) devices's I2C port using I2C slave mode.

see also [AVR Version](./AVR), [HybridMidiATtiny](https://github.com/mimuz/mimuz-avr-core/tree/master/arduino/libraries/HybridMidiAttiny)

# STM32 Version (STM32F042K6T6)

STM32 version of mi:muz:tuch (v0.2x) is my first STM32 project, it now only support USB Mode.

see also [STM32 Version](./STM32)

# Configurator

- [Sample](http://mz4u.net/tuch/)
- [Source](./configurator/)

# VID/PID

USB VID/PID pair for this application is provided by [pid.codes](http://pid.codes/).

> This Project is opensource. but if You folk this project to another product, USB VID/PID pair must be replaced to another codes. 

# Licenses

mi:muz:tuch under indivisual licences for AVR Version, STM32 Version and Configurator.
See Licences follow as:

- [Licences for AVR Version](./AVR/LICENSE.md)
- [Licences for STM32 Version](./STM32/LICENSE.md)
- [Licences for Configurator](./configurator/LICENSE.md)



