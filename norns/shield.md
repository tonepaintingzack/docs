---
layout: default
title: norns shield
has_toc: false
---

![](https://monome.org/docs/norns/images/norns-shield.png)

# norns shield

a DIY circuit which extends a normal Raspberry Pi, turning it into a norns.

the norns shield is [open source hardware](https://github.com/monome/norns-shield). monome sells a complete kit so that you can get straight to making sound and code.

## requirements

- [raspberry pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b) ($35) important! other models are not compatible.
- sd card - use a high quality brand such as [SanDisk](https://www.adafruit.com/product/2820) ($10)
- power supply - the Pi3B has a micro-USB power port and requires [at least 2A](https://www.adafruit.com/product/1995). you can also use a portable USB battery if it's sufficiently large.

## assembly

all you need is a normal philips screwdriver.

1. peel the clear acrylic cover. observe the orientation below to see which was is up. add the four short standoffs, using the four short screws.
2. press the black key caps on to the white keys. this takes a bit of force, and you will hear a satisfying snap. press the knob caps into the top of the knobs, the put the on the encoders.
3. peel the protective sheet away from the screen. the acrylic assembly will fit over the top, poking the threads through the circuit board. flip it over and add the longer standoffs. the short standoffs go near the audio jacks. hand-tightening is sufficient.
4. attach the raspberry pi. attach the white case. add four long screws to secure the case. add the rubber feet.
5. read on for instructions on flashing your sd card.

![](https://monome.org/docs/norns/images/norns-shield-assembly1.png)

![](https://monome.org/docs/norns/images/norns-shield-assembly2.png)

![](https://monome.org/docs/norns/images/norns-shield-assembly3.png)

![](https://monome.org/docs/norns/images/norns-shield-assembly4.png)


## flashing sd card

1. download and install [etcher](https://www.balena.io/etcher/)
2. get the [current image](https://github.com/monome/norns-image/releases/download/201029/norns201029-shield.zip)
3. run etcher, it's very straightforward. be aware that your sdcard will be erased!