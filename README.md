# ATTiny-Widget
Just a simple board that has two ATTiny processors powered by a micro USB connector. The rest is up to you!

<a href="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/2016-11-12 22.18.42.jpg"><img src="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/2016-11-12 22.18.42.jpg" width="400"></a>

This project was basically an experient in order to try out a new (to me) schematic capture and PCB designer tool called [DipTrace](http://diptrace.com/). Overall, I liked diptrace to make a tiny PCB like this. I would not consider this to be anywhere near equivalent to professional packages like Altium. 

I also used this project as an excuse to purchase a solder paste stencil from [OSH Stencils](https://www.oshstencils.com/#) and to play with my new [hot air repwork station from Sparkfun](https://www.sparkfun.com/products/10706). This board *IS* hand solderable! Infact the first of the boards that I assembled, I did by hand. The only tricky component was the usb connector. I was able to do this fairly easy using the drag-soldering technique.

## Details
<a href="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/schematic.png"><img src="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/schematic.png" width="600"></a>

Micro USB power input to two ATTiny MCU's. There are two different ATTinys on this board. An ATTiny84 and an ATTiny85. These MCUs are great because they can be used with no additional components. Infact, on this board, the only additonal components are some filter capacitors for the power rail and a header for the programmer interface.

Other than that, the board is just a widget that can be used to add a little bit of logic to anything. I have exposed an array of copper pads for every pin. This makes it easy to add LEDs or to wire to just about any sensor.

<a href="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/pcb.png"><img src="https://raw.githubusercontent.com/jonmash/ATTiny-Widget/Images/pcb.png" width="400"></a>

## BOM
|Ref |Value | Name              | Pattern                | Manufacturer    | Quantity |
|:--:|:----:|:-----------------:|:----------------------:|:---------------:|:-:|
| C1 | 1u   | CC0805KKX7R7BB105 | CAP_0805               | Yageo           | 1 |
| C2 | 0.1u | C0805C104K4RACTU  | CAP_0805               | Kemet           | 1 |
| C3 | 0.1u | C0805C104K4RACTU  | CAP_0805               | Kemet           | 1 |
| J1 |      | 1981568-1         | 1981568-1              | TE Connectivity | 1 |
| J2 |      | 15910060          | HDR-2x3S/2.54x2.54/8x6 | Molex           | 1 |
| J3 |      | 15910060          | HDR-2x3S/2.54x2.54/    | Molex           | 1 |
| U1 |      | ATTINY84_SOIC     | SOIC-14/150mil         | Atmel           | 1 |
| U2 |      | ATTINY85_SOIC     | SOIC-8/209mil          | Atmel           | 1 |
