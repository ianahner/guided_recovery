# Guided Parachute Recovery System

## Overview
This system should be capable of returning a payload to a set location after a flight concludes. This system is designed for use on high altitude balloons and rockets. 

## Hardware
- STM32F405RGT6TR (TQFP 64)
- BNO080 on I2C1 (with resistive heater on opposite board side)
- BME280 on I2C2
- NEO-M8Q on UART3
- PCB mount GPS antenna
- 2S lipo BMS
- Vin sense
- Vin -> 3v3 buck
- 3 0805 Leds (Blue, White, Red)
- 4 servo ports
- n open drain outputs (3-5A max current)
- Debug via SWD + UART out (UART 1)
- USB micro (only data)

