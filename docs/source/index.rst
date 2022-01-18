Sense Node C3
====================================

.. image:: ../images/irm-mini-front.png

Sense Node C3 is a sensor node base for your smart home. You can solder on different sensors on it to create your own custom node.
With the little proto area, you can easily create your own custom node. Like a PIR sensor with photoresistor to light up a night light at night.

It's make for Home Assistant with ESPHome, but compatible for almost all other IoT Platform like Blynk, AWS IoT, Azure IoT, etc. Or even your own simple IoT Platform.

Specifications
-------------

- Input: USB Type C 5V or 3 x AAA batteries
- Power Consumption: ~0.5W
- Core: ESP32-C3-mini1-N4
- 2 x onboard buttons (EN and IO9)
- 1 x onboard WS2812B LED (IO8)
- battery level (IO0)
- on board proto area for soldering sensors on.
- on/off switch
- onboard power status LED
- MP3416 Power management IC
- QWIIC I2C interface


.. toctree::
   :maxdepth: 3

   hardware
   software
   faq
