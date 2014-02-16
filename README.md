Clock
=====

This project used ATmega8535 (16 MHz)

Features I used

- External Interrupt(INT0,1,2)
- PORTD pin 4 to 7 to materialize dynamic display for 7-segment (Of course used npn TR - 1815)
- PORTA pin 0 to 7 to turn on the numbers on 7-segment
- PORTC for External Interrupt
- I2C, DS1307 library provided by CodeVisionAVR
- Eagles Cad (Schmatic Added but its not quite done yet)
- 


Need to be fixed

- Chattering. I heard there is a way to prevent this only in software. 
  Someone give me a hint a good way to prevent it please!

- Bigger FND(7-Segment) - Couldn't because of the current problem of TR.. 
    The limit of it was too low to run the bigger FND
