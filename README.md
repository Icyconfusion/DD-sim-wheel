# DD-sim-wheel
A Direct Drive (DD) wheel for simracing using a hoverboard motor and CAN bus.

I designed this wheel for simracing, to compete with high end direct drive wheels that offer great quality force feedback, except with a much lower price. The wheel has the capability to connect wheel rims, pedals, shifters, handbrakes etc and send those inputs, along with steering position to the PC as game inputs. In creating this project, I learned a lot about motor control and half bridge drivers.

# Assembly

The project can be separated into two parts, the wheelbase and the wheel rim.

For the wheelbase, the assembly consists of four horizontal 2020 profiles, allowing for mounting to rigs etc, and providing the basic structure of the base. Two vertical posts are attached by 90 degree connectors to enable mounting the cross beam for the motor.

(Insert pic here)

The crossbeam (2040 profile) is important as it is the base structure for supporting and holding the motor in place. A thin steel plate (necessary to prevent damage and subsequent twisting of the the crossbeam as a result of the motor axle) is attached to the profile, with the flat part of the motor axle being locked on with the 3d printed clamp. This is the mechanism for holding the motor in place and preventing rotation in the axle. 

(Insert pic here)

To prepare the motor, it is first necessary to disassemble it. First remove the tire as this wont be needed. Then remove the motor bell as we will need to drill holes into it. We will also need to drill into the axle. a 6x70mm bolt pattern is drilled in to the bell face, as well as a 30mm hole in the centre. This allows the mounting of the encoder and routing of wires. Drill a hole in the closed end of the axle, so that wires can run through.

(Insert pics here)

The MT6701 encoder is attached to its mount, then press fit into the bearing on the bell side of the motor.

(insert pic here)

The diametric magnet for the encoder is glued into the hole on the inside of the magnet mount, this will be attached to the motor along with the quick release using the 6x70mm drilled holes.

(insert pics here)

The side covers attach to the four horizontal profiles using T nuts, and the PSU is mounted to the side cover using the mounting threads in the psu. The PCB is attached to its mount using the mounting holes, then attached to the vertical profile.

(insert pics here)

The USB C connectors are screwed onto the back plate, and power cables run through the two holes. The back, top and bottom plates/covers are mounted using T nuts.

(insert pics here)

The front plate is screwed directly into the tapped ends of the profiles. This is the wheelbase assembly.
(insert pic here)

For the wheel rim assembly, is is as simple as mounting the 12mm buttons using the nuts included, running the cable from the mcu into the USB c connector in the quick release, and then mounting the wheel rim, buttons box/plates and quick release using screws, and then pushing onto wheelbase.

(Insert pics here)

# Electronics

### Schematic

### PCB

### Wiring

# Firmware

The wheelbase uses a modified version of OpenFFBoard firmware. OpenFFboard controls the motor including torque, responding to output from the PC/game to provide force feedback. I added my own CAN firmware into this to recieve CAN messages as inputs, and send them to the PC. This included writing my own CAN callback into the firmware.
For the wheel rim MCU, I wrote my own firmware for reading button inputs, and then sending via CAN bus. The MCU will only send a message when their is a change in button states e.g a press or release, this is to reduce interruption to the motor control firmware. The can message is as follows: if button one is pressed, then 00000001, which is 1x01. Or if buttons 1 and 4 are pressed, 00001001, 0x09.

# BOM

### Parts

### Printed parts

| Name| Quantity|Picture|
|---|---|---|
|Side cover| 1|
|PSU side cover| 1|
|Top plate | 1|
|Top cover| 1|
|Bottom cover| 1|
|Back cover| 1|
|Front cover| 1|
|Axle clamp| 1|
|Encoder module| 1|
|Magnet module| 1|
|PCB mount| 1|
|Wheel button plate| 1|

