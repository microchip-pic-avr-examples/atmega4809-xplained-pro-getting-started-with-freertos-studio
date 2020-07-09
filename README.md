<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

![Freertos](images/freeRTOS.png)

# ATMEGA4809 Xplained Pro Getting Started With FreeRTOS™

This is an example of how to get started with FreeRTOS™ on the AVR architecture with ATMEGA4809 Xplained Pro. FreeRTOS™ is a real-time operative system kernel which allows the MCU to operate with different tasks simultaneously. This is accomplished with mutexes, semaphores and software timers. [AN3007](#Related-Documentation) describes in detail how the FreeRTOS™ is being used to control the AVR.

## Related Documentation

- [AN3007 - Getting Started with FreeRTOS on megaAVR® 0-series](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en610121)
- [ATmega4809 Device Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [FreeRTOS™ Homepage](https://www.freertos.org/index.html)

## Software Used

- [Atmel Studio 7.0.2397 or later](https://www.microchip.com/mplab/avr-support/atmel-studio-7)
- ATmega_DFP 1.4.351 or later

## Hardware Used

- [ATmega4809 Xplained Pro](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)
- [OLED1 Xplained Pro Extension Kit](https://www.microchip.com/developmenttools/ProductDetails/ATOLED1-XPRO)

## Setup

* Connect the OLED1 Xplained Pro Extension Kit into the **EXT3** port on your Xplained Pro
* Connect the ATmega4809 Xplained Pro to your computer with a micro usb cable.

## Operation

1. Download the zip file or clone the example to get the source code
2. Open `ATmega4809FreeRTOSExample.atsln` in Atmel Studio
3. In your menu bar in Atmel Studio go to `Debug->Start Without Debugging` or press `CTRL + ALT + F5`
4. Open data visualizer under `Tools->Data Visualizer` to interact with the virtual comport on the devkit

## Conclusion

We have here shown that it is possible to run FreeRTOS™ on an ATmega4809 and what advantages this might bring to your project. As mentioned in the appnote [AN3007](#Related-Documentation) you can see the different tasks running and interact with them using the virtual com port on your ATmega4809 Curiosity Nano or using the on board buttons. 