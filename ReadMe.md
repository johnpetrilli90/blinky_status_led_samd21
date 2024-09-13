# Blink a Processor Status LED with SAMD21 Xplained Pro
A Microchip Studio project with the SAMD21 Xplained Pro as the target. 
- Configures the clock tree. 
- Configures the systick handler to generate a 1ms tick on a variable called `g_board_millis`. 
- Run LED0 on PB30 to blink from the board millis timer. 
- Puts the LED blink function in the main processor loop with the intention of being a visual indicator to determine if the MCU is execting and/or if it is bogged down.
- The blinky algorithm can be easily ported to other devices
