# Framework 2x CAN Interface Card

This is a 2x CAN to USB-C [budgetcan-fw](https://github.com/ryedwards/budgetcan-fw) based framework expansion card. It uses an STM32F405 as the cpu.

## Software

A forked and modified version of [budgetcan-fw](https://github.com/ryedwards/budgetcan-fw) for this board will follow shortly, however its pretty simple to adapt it to the STM32F405.

## Hardware
The expansion card has a 9-pin Würth Elektronik D-Sub connector with a pinning similar to the common Vektor VN1610 dongles. This means that the expansion card is not flush with the framework but has its connector "standing out". This is not pretty, but it allows using it without carrying another cable around.

The USB connector is a MOLEX 1054440001 connector which "sandwiches" the PCB.

A 3d printable case will follow shortly.

## Screenshots

![screenshot1](/assets/screenshot1.png)
![screenshot2](/assets/screenshot2.png)