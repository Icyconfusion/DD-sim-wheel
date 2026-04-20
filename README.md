# DD-sim-wheel
A Direct Drive (DD) wheel for simracing using a hoverboard motor and CAN bus.

I designed this wheel for simracing, to compete with high end direct drive wheels that offer great quality force feedback, except with a much lower price. The wheel has the capability to connect wheel rims, pedals, shifters, handbrakes etc and send those inputs, along with steering position to the PC as game inputs. In creating this project, I learned a lot about motor control and half bridge drivers.
<img width="939" height="691" alt="image" src="https://github.com/user-attachments/assets/09fcc837-f3d1-4af6-9a3a-dece3392ec9a" />

# Assembly

The project can be separated into two parts, the wheelbase and the wheel rim.

For the wheelbase, the assembly consists of four horizontal 2020 profiles, allowing for mounting to rigs etc, and providing the basic structure of the base. Two vertical posts are attached by 90 degree connectors to enable mounting the cross beam for the motor.

<img width="687" height="606" alt="image" src="https://github.com/user-attachments/assets/82337205-c691-4863-ac81-87b12e511b33" />

<img width="645" height="703" alt="image" src="https://github.com/user-attachments/assets/db663596-ac44-458b-9d8d-7a6794f17371" />


The crossbeam (2040 profile) is important as it is the base structure for supporting and holding the motor in place. A thin steel plate (necessary to prevent damage and subsequent twisting of the the crossbeam as a result of the motor axle) is attached to the profile, with the flat part of the motor axle being locked on with the 3d printed clamp. This is the mechanism for holding the motor in place and preventing rotation in the axle. 

<img width="476" height="414" alt="image" src="https://github.com/user-attachments/assets/1e561749-a4bd-4a3d-8fdb-723b556c30eb" />

<img width="1104" height="708" alt="image" src="https://github.com/user-attachments/assets/dc3cb34a-b2ce-4a7f-b76f-8b10306592bc" />


To prepare the motor, it is first necessary to disassemble it. First remove the tire as this wont be needed. Then remove the motor bell as we will need to drill holes into it. We will also need to drill into the axle. a 6x70mm bolt pattern is drilled in to the bell face, as well as a 30mm hole in the centre. This allows the mounting of the encoder and routing of wires. Drill a hole in the closed end of the axle, so that wires can run through.

<img width="1108" height="805" alt="image" src="https://github.com/user-attachments/assets/b0a49478-e77a-4f34-97ec-14132b0dbfb9" />


The MT6701 encoder is attached to its mount, then press fit into the bearing on the bell side of the motor.

<img width="655" height="663" alt="image" src="https://github.com/user-attachments/assets/25a9cbba-308f-41fc-bbd6-845c308e86a7" />

<img width="883" height="792" alt="image" src="https://github.com/user-attachments/assets/e85c7be1-f5f5-4093-bf30-cdc7155fecbc" />


The diametric magnet for the encoder is glued into the hole on the inside of the magnet mount, this will be attached to the motor along with the quick release using the 6x70mm drilled holes.

<img width="833" height="743" alt="image" src="https://github.com/user-attachments/assets/3dc923d2-6706-4029-909c-a84f54ace390" />

<img width="583" height="573" alt="image" src="https://github.com/user-attachments/assets/115add28-766f-4aee-8c83-8bd195cf483f" />

<img width="799" height="662" alt="image" src="https://github.com/user-attachments/assets/c0cf0514-7c39-4c0f-91aa-e62af4b9a04f" />

The side covers attach to the four horizontal profiles using T nuts, and the PSU is mounted to the side cover using the mounting threads in the psu. The PCB is attached to its mount using the mounting holes, then attached to the vertical profile.

<img width="861" height="574" alt="image" src="https://github.com/user-attachments/assets/93048969-b91e-4760-8e65-e89fe2132673" />

<img width="777" height="708" alt="image" src="https://github.com/user-attachments/assets/5c7bde7d-b8da-439e-b68e-0d6e8d6df719" />

<img width="628" height="474" alt="image" src="https://github.com/user-attachments/assets/a679d5d2-ff5a-43f8-8be8-01a3a492a883" />

<img width="542" height="523" alt="image" src="https://github.com/user-attachments/assets/d6d35c5f-9128-4d52-b641-f13418223192" />

<img width="709" height="652" alt="image" src="https://github.com/user-attachments/assets/593ada93-57d1-4fbc-8a28-d728f47fc885" />


The USB C connectors are screwed onto the back plate, and power cables run through the two holes. The back, top and bottom plates/covers are mounted using T nuts.

<img width="660" height="556" alt="image" src="https://github.com/user-attachments/assets/afa3290e-1cb8-497f-9f70-d5544e0a132e" />

<img width="1008" height="517" alt="image" src="https://github.com/user-attachments/assets/24c4f645-7e6d-498e-8b4d-2f55f8f486f5" />

The front plate is screwed directly into the tapped ends of the profiles. This is the wheelbase assembly.

<img width="550" height="707" alt="image" src="https://github.com/user-attachments/assets/e1a33d92-5460-4627-ad09-c250b2b85345" />

<img width="921" height="689" alt="image" src="https://github.com/user-attachments/assets/d9fdf09b-e7ac-4b52-b94e-0139f7ce916b" />

<img width="757" height="674" alt="image" src="https://github.com/user-attachments/assets/e96c2fe1-c681-44f5-ba37-134c5bde1283" />

For the wheel rim assembly, is is as simple as mounting the 12mm buttons using the nuts included, running the cable from the mcu into the USB c connector in the quick release, and then mounting the wheel rim, buttons box/plates and quick release using screws, and then pushing onto wheelbase.

<img width="491" height="636" alt="image" src="https://github.com/user-attachments/assets/bee032d4-05f8-42dc-9c3b-f76bcab88194" />

<img width="975" height="695" alt="image" src="https://github.com/user-attachments/assets/a3887ee6-6b3b-4c9e-b9f1-b3f418b077a8" />

<img width="487" height="559" alt="image" src="https://github.com/user-attachments/assets/355a4d31-2422-4848-bd24-b13f3a41ed92" />

<img width="810" height="581" alt="image" src="https://github.com/user-attachments/assets/fdf1966c-1975-4e96-bd30-5ed6057249e9" />


# Electronics

### Schematic
<img width="1056" height="656" alt="image" src="https://github.com/user-attachments/assets/d969f6eb-dead-4d6f-8443-36ca8ec64328" />

I made my own 3 phase motor driver to handle the control of the hoverboard motor:
<img width="640" height="638" alt="image" src="https://github.com/user-attachments/assets/8c57497e-304a-4fc6-b488-e2b5b05c473e" />

It uses an INA240 for current sensing for torque control, and an IR2104 IC so that the STM32 can control the MOSFETS.

<img width="512" height="406" alt="image" src="https://github.com/user-attachments/assets/aab1314d-53ce-48a7-8838-1ba234071619" />

Screw terminals to external connections:
<img width="309" height="758" alt="image" src="https://github.com/user-attachments/assets/330fbd9b-67ce-482c-86c8-39982e935e0d" />

And brake resistor circuit:
<img width="722" height="633" alt="image" src="https://github.com/user-attachments/assets/814c50ea-a651-440b-a069-2022606c2553" />

### PCB

<img width="702" height="603" alt="image" src="https://github.com/user-attachments/assets/e5a59bb4-bded-4011-88c7-8a768aca1c75" />

It has M6 mounting holes for the wheelbase PCB mount. The PCB is organised with the motor driver at the top, and low voltage components below the STM32, which is connected by headers. It uses TO-220 mosfets, and 7.62mm screw terminals. The screw terminals on the bottom are to CAN connections, encoder and 5v power.

<img width="1521" height="494" alt="image" src="https://github.com/user-attachments/assets/d63d35e2-2715-46c1-89a4-0087b4ff37fa" />

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

