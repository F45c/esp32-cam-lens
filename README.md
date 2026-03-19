# Description

I'm building a camera system with a big adjustable objective lens for an esp32 and the zoom is adjusted by two micro servos.
Therefore, you can control the camera and the zoom using the esp32 over wifi.

I'm doing this so that I can build my own custom security camera and I needed zoom. In the future I might add more servos to rotate the entire camera. Also, I wanted to work with servo motors to learn how they work and how to control them.

![](https://github.com/F45c/esp32-cam-lens/blob/95b15149f01a7ac86738415cefdb0615431f0c87/3dmodel.png?raw=true)

### Here's the simple wiring diagram, it shows the two servos connected to the esp32-cam module:

The wiring is pretty simple:
- Connect the camera cable into the esp32's camera slot
- Connect the servos signal wires to GPIO15 and GPIO16
- Connect the servo GND and VCC pins to the corresponding pins on the esp32 (GND, 3V3)

  ![wiring diagram](https://github.com/F45c/esp32-cam-lens/blob/405aea4355f4187bf7702536961c2b9d10761148/wiring.png)



### This is what the final result looks like:


![final result](https://github.com/F45c/esp32-cam-lens/blob/284e94121c8dfd9dfcfefc42dc7ec183e39324e6/pictures/project_image.jpg)


### BOM (Bill of Materials):

| Name | Purpose | Cost Per Item (USD) | Quantity | Total (USD) | Link | Distributor |
|------|---------|---------------------|----------|-------------|------|-------------|
| Camera Cable FFC FPC extension board adapter 24P 0.5mm 200mm | The camera cable is too short, needed to connect to the esp32 | 6.42 | 1 | 6.42 | https://a.aliexpress.com/_EzdhGvO | Aliexpress |
|Esp32Cam Module| The esp32 module with camera connector for wifi camera | 16.99 | 1 | 16.99 | https://www.az-delivery.de/products/esp32-cam-modul-esp32-wifi-bluetooth-modul-inklusive-kamera?variant=32376084136032 | AZ-Delivery |
| OV5640 with lens mount 65 degrees| The camera and the M12 lens mount | 5.94 | 1 | 5.94 | https://a.aliexpress.com/_EJd6qTa | Aliexpress |
|6-22mm manual varifocal zoom lens | The lens that is adjusted by the servos | 13.76 | 1 | 13.76| https://de.aliexpress.com/item/32812351615.html | Aliexpress
| metal gear micro servo| Needs to be metal to have enough torque to move the lenses| 17.34 | 1 | 17.34 |https://www.az-delivery.de/products/mg90s-micro-servomotor?variant=32344287182944 | AZ-Delivery |

