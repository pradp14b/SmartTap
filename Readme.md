# Conserve Water - Make a water Tap more SmArt
An AVR Micro controller based prototype which uses water flow sensor and RGB leds. It can be fit into a water tap which will indicate the over usage of water using different colours indirectly creating a behavioral impact leading to conservation of water in our daily life.

# How does it works ?
A water flow sensor is used to find the amount of water that passes through that. When the water flow exceeds an acceptable limit, the MCU will gradually increase the intensity of RGB LED. The more we consume the more the intensity would be.

![SmartTap](https://github.com/pradp14b/SmartTap/blob/master/imgs/smart_tap.jpg)
![SmartTapSideView](https://github.com/pradp14b/SmartTap/blob/master/imgs/smart_tap_side_view.jpg)
![SmartTapAction](https://github.com/pradp14b/SmartTap/blob/master/imgs/smart_tap_action.jpg)

# Components
* AVR Microcontroller (Atmega 2560)
* Water flow sensor
* Neo Pixel RGB Led Ring.

![Connections](https://github.com/pradp14b/SmartTap/blob/master/imgs/connections.png)
 
![Water Flow Sensor](https://github.com/pradp14b/SmartTap/blob/master/imgs/flow_sensor.jpg)
 
![Neo Pixel Ring](https://github.com/pradp14b/SmartTap/blob/master/imgs/neopixel_ring.jpg)

# Futuristic Thoughts:

* Connect an ESP8266 (Wifi Module) to every tap
* Node based web server to collect and process the data from Wifi module
* Collect tons of data and do some Analytics ??





