# Troubleshooting
**Check the battery charge**

Dead batteries can cause a lot of strange problems to appear. If the robot was working and now is not, check the batteries.

Not where you want to be?

[Electronics guide](ELECTRONICS.md)

[README](README.md)

[Electronics guide](ELECTRONICS.md)

## Drive does not behave as expected:
1. Tell the robot to drive forward. Which way does it go?
If it turns, calibrate the ESCs again.
If it goes backward, check that the **blue** ESC wires are towards the **back** of the robot when the Repeat Drive logo is facing upwards.
1. Tell the robot to turn. What does it do?
If it turns the wrong way, check that the ESC wires are plugged into the correct transmitter channel as indicated by the markings on the chassis.
1. If the robot barely moves, moves erratically, or whines and does not move, check that the battery is fully charged.

## Robot does not turn on:
1. Check that the battery is fully charged.
1. Check that the wires from the power switch are fully connected to the power distribution blocks.
1. If the robot still does not turn on, the switch may be faulty.

## Motors whine and do not move or behave erratically:
1. Check that the servo is not trying to move past the limits of motion (eg. move the servo away from the ends of its range or set down anything it is holding). The servo can consume a lot of power when it is stalled and not leave enough for the drive motors.
1. Check that the battery is fully charged. Dead batteries cause many strange issues that can be difficult to debug.

## Servo moves erratically without telling it to move:
1. The battery is probably dead. Charge it or switch to a different battery.

## Other issue not addressed:
- Check out the [electronics guide](ELECTRONICS.md) for a description of what each part does. Think through the path from the battery, through the switch, and to the part that is not working.
Knowing what each part does and what are the signals that it is or is not working will allow you to make a educated guess of what the issue is.
- Checking all the wire connections is also a good idea.
