SN3218
======

A MicroPython driver for the SN3218 18-channel PWM LED driver.

Features:

- Python and Arduino implementations of drivers
- Default gamma correction (overridable per channel)

API:

enable()

disable()

reset()

enable_leds(int mask)

channel_gamma(int channel, list gamma)

output(list values)
