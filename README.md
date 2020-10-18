# Mini Remote Control R2D2

This repo is for my mini remote control R2D2 project. It includes all the stl files, all the code files, and the f3d (Fusion 360) file. It also includes some Fusion 360 renders and some extra images.

## Prerequisites
All you need is access to a 3D printer, some skills with through-hole soldering and the parts needed.

## Assembly
First solder the components on to the PCB, making sure that they are the right way around and aligned with the silkscreen. Then place the main PCB in the bottom of the body. Place the motors in the mounts in the feet and push the wires through the feet and legs. Then push and glue if necessary the foot to the corresponding leg, eg left foot to left leg. Then push the legs through the holes in the body, making sure to get the in the right orientation, then push the fastening bolt through the holes to secure the legs in the correct position, then glue them. Repeat for the other leg. For the center foot, put the axle through the wheel and glue the axle in place, not the wheel. For the head mechanism, put the motor inside the head stem with the motor lock glued in place under it, then slide the head stem on to the pegs pointing upwards from the body, from there, put the head on to the head stem with some glue. You then plug the wires into the main PCB, turn it on and put the head on top. For the controller, solder the components on and enjoy. (The wheels are lego wheels as they are what I have handy from siblings and will probably be changed in the coming time.)

## Programming
Plug the ATmega328P into a programmer and burn the bootloader if it doesnt already have one. Then upload the corresponding sketch and put the IC in the proper socket.

## Parts
### Main PCB
* ATmega328P Digikey x1
* LD1117V33 (COM-00526) Sparkfun/Core Electronics x1
* NRF24L01 x1
* NPN Transistor (COM-00521) Sparkfun/Core Electronics x12
* 4xAA Battery Holder (PRT-12083) Sparkfun/Core Electronics x1
* 0.1uF Ceramic Capacitor (COM-08375) Sparkfun/Core Electronics x1

### Controller PCB
* ATmega328P Digikey x1
* LD1117V33 (COM-00526) Sparkfun/Core Electronics x1
* Thumb Joystick (COM-09032) Sparkfun/Core Electronics x2
* NRF24L01 x1
* 4xAA Battery Holder (PRT-12083) Sparkfun/Core Electronics x1

## Renders
![alt text](https://raw.githubusercontent.com/Zachary-Greene/RC-R2D2/master/Images/R2D2%20Render%20(2-3-2).PNG "R2D2 2-3-2 Configuration")
![alt text](https://raw.githubusercontent.com/Zachary-Greene/RC-R2D2/master/Images/R2D2%20Render%20(2-2).png "R2D2 2-2 Configuration")

## License
See LICENSE.md
