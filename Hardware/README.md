# _SUB_HW_EPaper

- __What is this board?__ This board will display the stored picture on the serial flash eeprom.
- __How will this board communicate?__ This eeprom on this board will be programmed by provided SPI pin. While it's under programming the MCU will be kept at reset state.

## Features

- __MCU :__ PIC16F15223 
- __Inputs :__ SPI
- __Outputs :__ E-ink Display
- __Board Osc. Freq. :__ 32 MHz (Internal)
- __Working Voltage :__ 3VDC (Coin battery)
- __Current Consumption :__ N/A
- __Board Dimensions :__ N/A

# _SUB_HW_EPen

- __What is this board?__ This board will be used to write on the EPaper serial flash.
- __How will this board communicate?__ The data that has to be written on Epaper serial flash will be received from USB and it'll be written over SPI bus.

## Features

- __MCU :__ PIC16F15223 
- __Inputs :__ USB
- __Outputs :__ SPI
- __Board Osc. Freq. :__ 32 MHz (Internal)
- __Working Voltage :__ 5.5VDC (Powered by USB)
- __Current Consumption :__ N/A
- __Board Dimensions :__ N/A

