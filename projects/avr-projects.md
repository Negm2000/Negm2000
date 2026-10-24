# Bare-metal AVR projects

Two ATmega32 projects in C, with drivers written from the datasheet and no Arduino core.

## [ATmega32 driver framework](https://github.com/Negm2000/ATmega32-Star-Framework)

Personal project: GPIO, Timer0, UART and HD44780 LCD drivers, with register maps and interrupt vectors defined by hand. The clock demo combines the timer tick, serial port and display. Built with PlatformIO and flashed over USBasp.

## [Pedestrian traffic light](https://github.com/Negm2000/AVR-Traffic-Light)

Udacity EgFWD Embedded Systems project: separate lights for cars and pedestrians, stepped by Timer0 interrupts. The pedestrian button triggers an external interrupt and changes the sequence according to the current light state. Includes the SimulIDE circuit and compiled firmware.

[Back to the profile](../README.md)
