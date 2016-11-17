# Powerhat
An rpi hat to shut down the raspberry pi gracefully

This hat includes the eeprom and a real time clock. A normal 12v relay is "powered" by capacitors, and when the power is switched off, The rpi is told to shut down and the capacitors allow approx 45 seconds for it to shut down before the relay cuts the power
