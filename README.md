# polaris-pool-cleaner
Reverse engineering a Polaris P93/9300 robotic pool cleaner

Picked up a couple of non-functional Polaris P93 robotic pool cleaners. The 9300 is the same model but with a blue shell.

The robot is connected to the control unit with a 3 wire cable, which provides +28VDC, ground, and a single-wire LIN bus. 

The robot contains a 'waterproof' motor block (R0637800) which consists of a control board and 3 motors (pump, left drive, right drive). Seems that most failures of the motor block are caused by water ingress and/or bad bearings. The shaft seals on the drive motors just seem to be rubber augmented with marine grease.
