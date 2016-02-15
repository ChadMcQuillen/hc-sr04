# Linux Driver for Raspberry Pi and HC-SR04

![Raspberry Pi and HC-SR04](https://www.modmypi.com/image/data/tutorials/hc-sr04/hc-sr04-tut-8.JPG)

# Wiring

* http://www.modmypi.com/blog/hc-sr04-ultrasonic-range-sensor-on-the-raspberry-pi

# Build Environment

* https://github.com/ChadMcQuillen/docker-raspberry-pi-driver-cross-compiler

# Build

````
make -C /build/linux ARCH=arm CROSS_COMPILE=$CCPREFIX M=`pwd` modules
````

# Credit

* https://github.com/tanzilli/hc-sr04

