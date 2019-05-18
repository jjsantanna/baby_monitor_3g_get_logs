# About
This is a personal project for monitoring my first daughter (who will/was born in May/2019). The idea is to monitor her:

## Sensors
1. [TEMPERATURE + HUMIDITY] Adafruit Si7021
Note: The first idea was to connect both sensors, temperature and light level, in different GPIO pins. However both sensors work on I2C. There were some links to help with that, ex.[link1](https://www.instructables.com/id/Raspberry-PI-Multiple-I2c-Devices/) and [link2](https://docs.pycom.io/firmwareapi/pycom/machine/i2c.html); HOWEVER at the end I decided to connect both sensors in the same 2 I2C pins.

2. [LIGHT LEVEL] Adafruit TSL2591

3. [SCALE] HX711 load cell amplifier
Note: we also bought Sparkfun HX711 however it didn't work.
- https://github.com/learn2develop/hx711py

4. [NOISE AND VIDEO] Baby Monitor 3G (iOS and MacOS app)
- https://github.com/BastianPoe/owlet_api.git

5. [HEART RATE + OXIGENATION LEVEL] Owlet Smart Sock
- https://github.com/BastianPoe/owlet_api
- https://github.com/craigjmidwinter/pyowlet
- https://github.com/mbevand/owlet_monitor
- https://github.com/bobcat0070/python-owlet
- https://github.com/tescalada/python-owlet 
- https://github.com/arosequist/node-owlet

6. [SMART MIRROR] MagicMirror
- https://github.com/MichMich/MagicMirror
  - For the weather
    - https://github.com/jclarke0000/MMM-DarkSkyForecast


  
