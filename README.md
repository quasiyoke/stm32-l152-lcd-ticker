# STM32 L152 Discovery LCD example

This example microcontroller flash program displays `*HELLO` string on LCD screen of STM32 L152 Discovery board.

## Requirements

1. STM32 L152 Discovery board
1. GNU ARM Embedded toolchain,
1. OpenOCD
1. STLINK

## Flashing

Just connect your board through USB Mini-B cable and execute this:

```sh
make flash
```

`make` will download [libopencm3 library](https://github.com/libopencm3/libopencm3), build `.elf` file and flash it using OpenOCD.
