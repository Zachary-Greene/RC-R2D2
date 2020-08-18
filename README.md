# Mini Remote Control R2D2

This repo is for my mini remote control R2D2 project. It includes all the stl files, all the code files, and the f3d (Fusion 360) file. It also includes some Fusion 360 renders and some extra images.

## Prerequisites
All you need is access to a 3D printer, some skills with through-hole soldering and the parts needed.

## Assembly
First solder the components on to the PCB, making sure that they are the right way around and aligned with the silkscreen. Then place the main PCB in the bottom of the body. Place the motors in the mounts in the feet and push the wires through the feet and legs. Then push and glue if necessary the foot to the corresponding leg, eg left foot to left leg. Then push the legs through the holes in the body, making sure to get the in the right orientation, then push the fastening bolt through the holes to secure the legs in the correct position, then glue them. Repeat for the other leg. For the center foot, put the axle through the wheel and glue the axle in place, not the wheel. For the head wheel mounts, line them up with the groove in the head and glue them to the body. This method will most likely change to a more promising and secure method. Then put the motor in the motor mount inside the body and secure the head gear to the motor shaft. Then plug the wires into the main PCB, turn it on and put the head on top. For the controller, solder the components on and enjoy.

## Programming
Plug the ATmega328P into a programmer and burn the bootloader if it doesnt already have one. Then upload the corresponding sketch and put the IC in the proper socket.

## License
See LICENSE.md