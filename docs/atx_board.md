# ATX control board

To manage the power of your computer, you will need to install an ATX adapter board inside the case and connect it to the motherboard.

!!! warning "Apple's Mac computers are not ATX compatible as they lack the needed ATX headers, this is ONLY compatible with PC servers and desktops."

1. Connect the rainbow wires as follows to the board. Optionally print [the mounting plate](stl/atx/index.md){target=_blank} for the PCI slot on a 3D-printer. Assemble everything like on pictures below. Secure wires in any convenient way (we used soft ties).

    ??? example
        <img src="atx_board_1.jpg" />

        <img src="atx_board_2.jpg" />

        <img src="atx_board_3.jpg" />

2. Find the pins on the motherboard responsible for connecting the buttons and LEDs of the front panel of the case. Usually wires and connectors on the motherboard have designations. If you're not sure, check the documentation on your motherboard.

    ??? example
        <img src="atx_board_4.jpg" />

        <img src="atx_board_5.jpg" />

3. Place the ATX board nearby and, focusing on the signatures, connect the male pins to the female pin of the front panel wires, observing the polarity (the polarity is indicated on the ATX board).

    ??? example
        <img src="atx_board_6.jpg" />

4. Repeat the procedure with the female pin of the ATX board by connecting them to the motherboard connector. Check the documentation on your motherboard.

    ??? example
        <img src="atx_board_7.jpg" />

5. Install the ATX board into the PCI slot of the case and fix it with a screw, or use a different mounting method at your discretion.

    ??? example
        <img src="atx_board_8.jpg" />

        <img src="atx_board_9.jpg" />

6. Arrange the wires in a way that is convenient for you and fix them if necessary.

    ??? example
        <img src="atx_board_10.jpg" />

7. Connect the ATX board to PiKVM using a [straight Ethernet cable](https://www.home-network-help.com/straight.html). 2 pair/4 wire will NOT work, must be a 4 pair/8 wire.

    ??? example
        <img src="basic_back.jpg" />


## Pinout

??? note "ATX RJ-45 pinout"
    The pinout of the RJ-45 connector is the same on the AT and ATX adapter.

    <img src="rj45.jpg" />

??? note "ATX LED wiring example"
    <img src="atx_led.jpg" />
