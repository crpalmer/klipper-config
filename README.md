To build the firmware for the mini 5+ you need to change
(using make menuconfig) the following options:

Microcontroller Architecture >> SAM21 / SAMD21 / SAMD51 / SAMD5x
Processor Model >> SAME54P20
Clock Reference >> 25Mhz Crystal

To flash the firmware:

make flash FLASH_DEVICE=/dev/<device>
