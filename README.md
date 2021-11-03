# Retekess-v115-firmware
- Firmware version: 1.4, (bin);
This is firmware for chinese 3-band reciever/audio player called Retekess v115, also known as Tivdio v115,Audiomax SRW 710 or Kaimeda SRW 710S;
Firmware readed using CH341 USB programmer, from 16Mbit/2Mbyte SPI flash F25D16 manufacturer: FENTECH;
+ Firmware version 1.4;
# Specifications
- Supported audio formats: MP3/WAV/WMA;
- Supported radio bands:
- FM: 87-108 Mhz also can support 70-108 by adding 1Kohm smd 0603 smd resistor (smd code 102);
- AM(MW) with 10Khz stepping: 520-1710Khz;
- AM(MW) WITH 9 Khz stepping:522-1710Khz;
- SW 4.750-21.850Mhz;
- Tuner type: digital DSP
- Tuner IC: AKC6955
- MCU: Apotech AX2220
- LCD resolition: 128x64
- LCD driver: ST7567
- LFA: MIX2008
- LFA output power: 3W
- Speaker: 4 Ohm 3W (in fact 2w)
- Memory type: SD card, max 32Gb
- Power: Li-Ion baterry BL-5C 1000mAh 3.7v or 5V from USB input
- Recommended charging current: 500mA, max. 1A
#List of some electronic components
- ESD1: BAV99 ESD protection, default N.C
- ESD2: 1N4148 ESD protection
- Q3: S9018 UHF amp.
- Q1: AO3401 p-channel MOSFET, control charging process by MCU GPIO
- Q2 and Q4: S9014, which one of them control backlight
- R4: 300 KOhm smd0603
- C10: 10uF, default N.C
- C17: 4.7uF 
- R10: 1Kohm, default N.C
- R11: and R11: 10 Kohm
- R3: 100 Ohm
- R6: 2 KOhm
- R8: 10 KOhm
- Z1: 32.768Khz
- C20: uknown, maybe 100n
- L1: idealy used with C20 like LC filter(but on board put an resistor), reduces noise from SD card, rating uknown, i used 270nH and was satisfied
- L2 and L3: rating uknown, maybe reduces noise on SPI lines, I used 5.6nH
- IC1: 8-bit MCU, (see datasheet)
- Note: I find datasheet only for AX2210, it's older version of AX2220
- IC2: quad spi FLASH memory, 2Mbyte
- IC3: AKC6955 DSP radio tuner 
- IC4: Low frequency amp.
+ Thank you for using my work, I am from Ukraine and didn't know English very well, I apologize for the mistakes if there are any.
