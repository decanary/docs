# Technical Specs

On the hardware you can find the following:

- IP67 Waterproof (max 1 meter for 30 minutes)
- Nordic 64MHz nRF52840 ARM Cortex-M4 processor with Bluetooth LE
- 256kB RAM, 1MB on-chip flash, 8MB external flash
- 1.3 inch 176x176 always-on 3 bit colour LCD display (LPM013M126) with backlight
- Full touchscreen (6H hardness glass)
- GPS/Glonass receiver
- Heart rate monitor
- 3 Axis Accelerometer
- 3 Axis Magnetometer
- Air Pressure/Temperature sensor
- Vibration motor
- 200mAh battery, 4 week standby time
- 36mm x 43mm x 12mm watch body, with standard 20mm watch straps
- Full SWD debug port on rear of watch

The bangle js 2 depends on some open source software to run properly.

- [Bootloader](https://github.com/espruino/BangleApps/tree/master/apps/boot), this is responsible for letting the user switch between the watch and launcher, aswell as loading widgets and settings. It uses the technical id `boot`
- [Firmware](https://github.com/espruino/Espruino/blob/master/libs/banglejs/jswrap_bangle.c), I don't advise modifying this unless necessary - _almost everything_ can be done without writing a single line of C on the bangle js 2.

This doc is in construction!
