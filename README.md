# Weu: A dual screen microconsole powered by the CM4

Weu is a microconsole ment for people who 
want a fun and open source home console 
platform to play and make games. It has 
a controller with a 320x240 touch display 
that acts as a second screen and includes 
a speaker, haptic motor, and 6DOF motion 
sensor which will open up many possibilities 
for gameplay. The OS will be based on linux and
will come with a SDK that will allow you to use 
C/C++ and Lua to develop games software. The OS
will also support open graphics apis like openGL
and vulkan so you can use a lot of existing libraries.

# Other things i'm considering

- Optional lower level graphics API

# rough BOM:

Console:

- CM4 (4G ram 8 GB emmc SC0672): $55
- Esp32-wroom-32e: $4
- RP2040: $1
- USB-C socket: $0.172
- USB-A sockets: $0.1148
- Button: $0.0193
- Pcb: $5
- Extended parts cost: $12

Total (assuming 2 boards are soldered): $78

Controller:

- Esp32-wroom-32e: $4
- Screen: $2.28
- Battery: $9.95
- Speaker: $2.03
- Buttons: $9.24
- Joystick: $2.50
- ISM330DHCXTR (Motion sensor): $5.41
- MAX98357A (Audio DAC): $1.88
- USB-C socket: $0.172
- PCB: $5
- Extended parts cost: $12

Total (assuming 2 boards are soldered): $55

Extra:

- Solder: $11.48
- Flux: $11.95
- Solder wick: $2

Grand total: $159

