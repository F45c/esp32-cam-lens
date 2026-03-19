# Description

I'm building a camera system with a big adjustable objective lens for an esp32 and the zoom is adjusted by two micro servos.
Therefore, you can control the camera and the zoom using the esp32 over wifi.

I'm doing this so that I can build my own custom security camera and I needed zoom. In the future I might add more servos to rotate the entire camera. Also, I wanted to work with servo motors to learn how they work and how to control them.

![](https://github.com/F45c/esp32-cam-lens/blob/95b15149f01a7ac86738415cefdb0615431f0c87/3dmodel.png?raw=true)

The wiring is pretty simple:
- Connect the camera cable into the esp32's camera slot
- Connect the servos signal wires to GPIO15 and GPIO16
- Connect the servo GND and VCC pins to the corresponding pins on the esp32 (GND, 3V3)

  ![wiring diagram](https://github.com/F45c/esp32-cam-lens/blob/405aea4355f4187bf7702536961c2b9d10761148/wiring.png)

  I added my 3d model design as a blender file because I can't use fusion360 or something. Also, I made an .stl file for the parts (that is ready to be printed)
