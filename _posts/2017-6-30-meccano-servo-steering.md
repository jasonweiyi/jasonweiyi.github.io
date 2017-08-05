---
layout: post
title: Meccano servo steering
---
![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/1.jpg)

## Meccano driving system

This article explains how to use a 180 degree rotation servo to make steering mechanism in Meccano.
The existing Meccano driving system uses a DC motor to drive a vehicle; the vehicle only drives forward or backward and
it does not turn left or right. For example, in the following figure, the left part above the chassis is the DC motor.

## Adding steering

To Add steering, I decided use a 180 degree rotation servo. The spin arm of the servo pushes a steering bar left or
right to support steering. I used the Hitec HS-8b55 servo:

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/hs85bb.jpg)

The difficulty is to mount the servo on to the Meccano. After a few tries, it turns out that small Meccano
beams provides a good solution. I can screw smaller 3 hole beams to the mounting two mounting holes of the servo,
and those two 3 hole beams are separated by 4 Meccano holes so I can use another two 4 hole small means to make
a rectangle bounding box around the servo. This spacing property is very nice because it means that the bounding box
then can be easily attached to existing Meccano architecture. Note that standard Meccano bolt is to large to go through
the servo mounting holes, so I used some other thinner bolts. See the following figures:

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/2.jpg)

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/3.jpg)

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/4.jpg)

## Attaching servo to Meccano chassis

I used four supporting poles to hold the servo bounding box. Each pole is consists of three standard Meccano spacers,
and I used a long, thin bolt, not standard Meccano ones (because Meccano ones are not long enough) to mount them to
the chassis. Note that this mounting is due to the chassis that I am using and it is not ideal since it takes a lot
of vertical space. It will be easy to design other mounting mechanism given other types of chassis.

## Steering

To steer, the servo spin arm pushes a standard N-shaped Meccano metal part, see the following figures. I added two
additional bolts in the N-shaped part to reduce the spacing. Note the following two figures are the steering mechanism
with the N-shaped part detached to the steering bar.

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/5.jpg)

![_config.yml]({{ site.baseurl }}/images/meccano-servo-steering/6.jpg)


## Demo

This is the YouTube video [link](https://www.youtube.com/watch?v=fM0n_AsgoqU "link title") to show how the steering
works.

## Arduino Code

Here is the Arduino code

<script src="http://gist-it.appspot.com/https://github.com/jasonweiyi/robotics/blob/master/meccano_servo_steering/meccano_servo_steering.ino"></script>

[Source code link](https://github.com/jasonweiyi/robotics/blob/master/meccano_servo_steering/meccano_servo_steering.ino)











