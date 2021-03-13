# Logic-level-converter-board
A bi-directional high-speed TTL-Compatible level shifter board 5V &lt;-> 3V3 for tinkering


***

<a href="images/screenshot_pic1.png">
<img src="images/screenshot_pic1.png" width="312" height="296">
</a>
<a href="images/screenshot_pic2.png">
<img src="images/screenshot_pic2.png" width="312" height="296">
</a>
<a href="images/SW_7x7x12mm_DPDT.jpg">
<img src="images/SW_7x7x12mm_DPDT.jpg" width="200" height="200">
</a>



    BOM
    ------------------------
    D1 2.54 mm pin pitch LED Diode (optional Power on/off indicator)
    R1  1206 approx. 100-330 Ohm (populate if D1, calculate suitable resistor value to use with D1)
    C1  1210 10-100 uF
    C2  1206 0.1 uF 
    Pushbutton switch SW_7x7x12mm_DPDT
    Barell Jack 5.5x2.1mm
    SN74CBTD16211 TSSOP-56_6.1x14mm_P0.5mm
    Power +5V center pin positive or via pinheader (verify polarity before connecting)
    2.54 mm jumpers to enable/disable /1OE (first 12-bits) and /2OE (second 12-bits), either enable with GND or disable via VCC.
    2.54 mm jumpers to disable unused inputs via jumper to GND.
    A lot of 2.54mm pinheader strips.

https://www.ti.com/lit/ds/symlink/sn74cbtd16211.pdf

Happy Tinkering!
