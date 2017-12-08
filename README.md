# XboxPiDroid
Setup of Raspberry Pi to use an XBox Controller


Requires that xboxdrv be installed first:
Link: https://github.com/FRC4564/Xbox

cmd: sudo apt-get install xboxdrv

To test the driver, issue the following command and see if the controller inputs are recognized

cmd: sudo xboxdrv --detach-kernel-driver

Run the sample:

cmd: cd Xbox
cmd: sudo python sample.py
