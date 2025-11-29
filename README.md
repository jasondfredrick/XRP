# XRP
XRP repository to support a XRP workshop

There are 5 [XRP-beta](https://docs.wpilib.org/en/stable/docs/xrp-robot/index.html) robots for Iron Kodiaks FRC Team 5137 to use, each with Quantity 4 1.2V 2400mAH AA batteries and a 6-ft micro-USB to USB A cable.

The latest [XRP-WPILib firmware](https://github.com/wpilibsuite/xrp-wpilib-firmware/releases) has already been loaded on each XRP. 

Each XRP has had its SSID renamed to XRP-# and has been labeled with the # on its undercarriage, where # is 1 through 5.

**Using the XRP**
1. Build Robot Code.
2. Power on XRP on a flat surface.
3. wait for green LED to stop blinking - this means IMU calibration complete.
4. Connect to XRP-# WiFi network, where # is 1-5, listed on the underside of the robot (password: xrp-wpilib).
4a. In unable to connect, plug in a micro-USB cable to your PC; a drive labeled "PICODISK" will mount inside there will be a XRP-Status.txt with WiFi information.
5. Simulate Robot Code - robot code is not deployed to the XRP like the RoboRIO, rather it communicates with WPI simulation.