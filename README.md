# NES controller USB interface.





This is just a simple project to interface the NES controller with USB via the
Arduino pro micro.

The Code simply Reads the Values from the NES controller's PISO shift reg and 
turns them into usb keyboard inputs.

The NES port can be found [here](https://www.zedlabz.com/products/controller-connector-port-for-nintendo-nes-console-7-pin-90-degree-replacement-2-pack-black-zedlabz?_pos=8&_sid=b3d25e834&_ss=r).


## To-Do

- [x] Create port footprint from technical drawing.
- [x] Create port 3D model from technical drawing.
- [ ] design Circuit diagram.
- [ ] Write code.
- [ ] design PCB.
- [ ] design housing.
- [ ] Assemble PCB and housing.

## keep In mind.

It requires quite a bit of force to remove the nes controller from the port,
this should influence the design of the housing, as to not add strain to the
solder joins or the pcb.


# Reference

[NES Port Technical Drawing](https://www.raphnet-tech.com/products/nes_controller_connector/index.php)  
[NES Port Pin out](https://www.raspberryfield.life/2018/09/01/nespi-project-part-4-the-nes-controller-protocol/)

