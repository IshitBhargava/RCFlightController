# RCFlightController
Flight Controller which runs INAV or Betaflight on a STM32 board for planes and multirotors

<b>RCFlightController</b> is a flight controller that has a F411 microcontroller, Plug-and-play GPS interface, Plug-and-play power module interface and RC Input port (with telemetry output) and a soft-serial port. All these interfaces are present on easy-to-use DF13 connectors. There are 4 main and 4 aux outputs on the board with <b>Redundant</b> power system. Board has SD-CARD socket for on-board logging and also includes on-board buzzer, and PinIO led + WS2812B Led. Additional WS2812B LEDS can be connected to the board using the 3 pin Servo-style interface.

# Hardware:

The hardware is based on the v1.0 and v1.1 boards, whose gerber files and <i>fritzing</i> design files have been attached. There is no major difference between the v1.0 and v1.1 boards, except that you can connect external i2c devices via the 2 (unconnected on v1.0) of the 6 pins on the GPS DF13 connector. 

# Supported expansion devices:

<table>
  <tr>
    <th>Interface</th>
    <th>Device(s)</th>
  </tr>
  <tr>
    <td>I2C</td>
    <td>VL53L0X, VL53L1X, Barometer*, Compass**, Airspeed***</td>
  </tr>
  <tr>
    <td>Serial</td>
    <td>Optical flow</td>
  </tr>
  
</table>

<subscript>hello</subscript>


