# Custom_Bootloader_Using_Stm32f429


This is simple UART bootloader based on ARM architecture with python host application. it is used to flash .bin user image and do some other useful features descriped below.

Hardware board used is stm32f429 Discovery board 

Features
01# Flash user app as .bin Image at any selected sector with its CRC32 used for Image integrity and verification. s).


02# verify user code before jump and run it.


03# Erase selected sectors.

04# Read any number of Bytes starting from selected sector.

05# read one-time-programming OTP section.


06# Read the read protection state
.


07# jump to any flash sector to run user app if pass CRC32 check successfully or enter do_nothing if not).



08# Get MCU ID.



09# Get bootloader version.


