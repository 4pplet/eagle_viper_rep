# Viper/Eagle REP

Replacement PCB for Viper/Eagle V2/V3

## Status:
Initial prototypes ordered and tested. QMK not added to main branch, use Eagle/Viper branch on my QMK fork.

## Some features:
- QMK & VIA
- USB Mini
- STM32F072CB
- in-switich leds
- ISO and ANSI
- Underglow

## Layout support: 
![alt text](./readme-images/layout_support.jpg "Layout support")

## Altium view of PCB - Solder
![alt text](./readme-images/eagle_viper_rep-MX_Rev_A1.jpg "PCB View - Rev A")

## Revisions:
- Rev A1: Initial prototype

## Todo:
- Move LED401 1mm to the right
- Try and implement proper SPI-driver for underglow (software driver currently)
- Try and implement proper PWM-driver for in switch leds (software driver currently)
- Add QMK and VIA support to main repos.
- Change resistor for in switch leds from 680R to 470R
