# STBee_F4mini
These are MicroPython board defintion files for STBee F4mini.

The product page can be found here: https://strawberry-linux.com/catalog/items?code=32405 (It's only in Japanese.)  
The Product schematic can be found here: https://strawberry-linux.com/pub/f4mini-sch2.pdf

Build the firmware using:
~~~
cd micropython/ports/stm32/boards
git clone https://github.com/forester3/STBee_F4mini
cd ..
make BOARD=STBee_F4mini
~~~
