# MAVLink Dev Guide

![](images/mavlink-logo.png)

*MAVLink is a very lightweight, header-only message marshalling library for micro air vehicles.*

It can pack C-structs over serial channels with high effiency and send these packets to the ground control station. It is extensively tested on the PX4, PIXHAWK, APM and Parrot AR.Drone platforms and serves there as communication backbone for the MCU/IMU communication as well as for Linux interprocess and ground link communication.

MAVLink was first released early 2009 by Lorenz Meier under LGPL license.

To run locally:

```
gitbook install
gitbook serve
```
