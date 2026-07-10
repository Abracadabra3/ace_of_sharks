# ELectronics guide
**This is a description of what each electronic part does and some of the signals that will tell you when it is or is not working.**

## Transmitter
The transmitter is the controller that sends (or transmits) the input you provide to tell motors what to do.
Transmitters and recievers must be connected, or bound, to each other. You can think of this like telling the reciever to only listen to a specific voice. If they are not bound, the robot will turn on but do nothing.

## Reciever
The reciever is the part that recieves the signals sent by the transmitter. A LED plugged into the `BATTERY` channel will light up when the reciever is on and turn off when the reciever is off.

## ESC
ESC stands for Electronic Speed Controller. This is the brain of the motors, and it takes the instructions from the reciever and turns it into power flickers (like a dimming light switch) to make the motor go fast or slow.

Fingertech Tiny ESCs have a red and green LED on them. If the lights are slowly blinking red, that means that the reciever is not connected to the transmitter. (You can see what this looks like by turning the robot on with the transmitter off.)

The LEDs also show what way the ESC is telling the motor to go. One way is red, the other way is green. How fast the lights are flashing is proportionate to how fast the motor should be going.

**If you are troubleshooting anything in your robot, see what the ESC LEDs are doing. This is a great troubleshooting tool.**

## Brushed drive motors
These motors are what make the wheels move. They have no smart components at all. Simiarly to a lightbulb, if they have power, they move. If they don't have power, they don't.

It can be fun to dissasemble a broken motor to see all the tiny gears and the other internal components like the brushes (thin metal strips on the black plastic piece on the back of the motor) and the coils (cut the gear off the shaft and push the shaft out).
## Servo
A servo is a special kind of motor that knows exactly where in its rotation it is. They have high precision and torque, which makes it great for powering a lifter type weapon. These do not need an ESC, as they take as an input the kind of signal the reciever outputs.

## Power distribution blocks
These connect multiple wires together so all the electronics are connected to power and ground.

## Switch
This part does exactly what the name sounds like it does: is turns the robot on and off. If this part is broken, the robot will not turn on when you tell it to.

## Battery
Just for completeness, the battery supplies power to the robot through the switch. If the battery is dead, this can cause a lot of weird problems.

## PWM cables
PWM stands for Pusle Width Modulation. The cable flashes power at different speeds to indicate different positions to the servo or the ESC. This is the kind of cable the servo uses and is pluggled into your reciever. The red wire is power, the brown wire is ground and the orange/yellow wire is signal. The power wire is in the middle, so nothing will blow up if it gets plugged in backwards.
