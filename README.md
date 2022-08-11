SparkFun MicroMod GNSS Function Board - NEO-M9N
========================================

[![SparkFun MicroMod GNSS Function Board - NEO-M9N](https://cdn.sparkfun.com/assets/parts/1/7/7/6/1/NEOM9N_01.jpg)](https://www.sparkfun.com/products/18378)

[*SparkFun MicroMod GNSS Function Board - NEO-M9N (GPS-18378)*](https://www.sparkfun.com/products/18378)

The SparkFun NEO-M9N GNSS Function Board is a high quality, geospatial board with equally impressive configuration options. The NEO-M9N module that is populated on this board is a 92-channel u-blox M9 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~1.5 meter accuracy. This Function Board supports concurrent reception of four GNSS. This maximizes position accuracy in challenging conditions, increasing precision and decreases lock time; and thanks to the on-board rechargeable battery, you'll have backup power enabling the GPS to get a hot lock within seconds!

Utilizing our handy M.2 MicroMod connector, no soldering is required to connect it to your system. Simply match up the key on your processor and function board's beveled edge connector to their respective key on the M.2 connector, then secure them to the Main Board with screws. Once connected, you'll have the option of choosing either the UART, SPI, or I<sup>2</sup>C (u-blox calls this Display Data Channel) port to communicate with the NEO-M9N.

The NEO-M9N module detects jamming and spoofing events and can reports them to the host, so that the system can react to such events. A SAW (Surface Acoustic Wave) filter combined with an LNA (Low Noise Amplifier) in the RF path is integrated into the NEO-M9N module which allows normal operation even under strong RF interferences.

U-blox based GPS products are configurable using the popular, but dense, Windows program called u-center. Plenty of different functions can be configured on the NEO-M9N: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc. All of this can be done within the [SparkFun Arduino Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library) via the I<sup>2</sup>C bus!

The SparkFun GNSS Function Board - NEO-M9N includes a USB type C connector when configuring the module with u-center. Power is provided through the Function Board's edge pins and regulated down through the 3.3V voltage regulator. Two status LEDs are also included for 3V3 and PPS, which can be disabled by cutting the jumpers on the back of the board. A 1x3 header is populated on the board and includes a 2-pin selectable jumper when selecting the communication protocol between SPI or Serial/I<sup>2</sup>C. For advanced users, there are jumpers to disable the write protection for the EEPROM (WP), disconnecting the pull-up resistors (I2C), and placing the module in safe boot mode (SAFEBOOT). A U.FL connector is provided to connect a GNSS antenna of your choice to the module.  The board is equipped with an on-board rechargeable battery that provides power to the RTC on the NEO-M9N.  This reduces the time-to-first fix from a cold start (~24s) to a hot start (~2s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time. 

Repository Contents
-------------------

* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library/all)** - Basic information on how to install an Arduino library.
* **[Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)** - Arduino Library the SparkFun MicroMod GNSS Function Board - NEO-M9N.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/1999)** - Basic hookup guide for the SparkFun MicroMod GNSS Function Board - NEO-M9N.


Product Versions
----------------

* [GPS-18378](https://www.sparkfun.com/products/18378) - Initial release


Version History
---------------

* v1.2 - Initial Release


License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
