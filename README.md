# Labbe-Mini

This is a project that helped me learn how to make keyboards, this might also help anyone thinking of making their own PCB.

Before opening it on Kicad download the following libraries and place them in the root folder inside ExtLibraries folder (create the folder):
* https://github.com/KiCad/Housings_QFP.pretty (should be named Housings_QFP.pretty)
* https://github.com/tmk/keyboard_parts.pretty (should be named keyboard_parts.pretty)
* https://github.com/tmk/kicad_lib_tmk (should be named kicad_lib_tmk-master)
* https://github.com/sszczep/kicad-libraries (should be named kicad-libraries-master)

Some nice pictures of the keyboard

![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/pcb.png)
![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/render.png)
![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/IMG_1779.jpg)
![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/IMG_1780.jpg)
![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/IMG_1782.jpg)
![alt text](https://github.com/alabbe9545/Labbe-Mini/blob/main/images/IMG_1783.jpg)

Pieces needed
* 4 x WS2812B 5050 RGB LEDs (https://aliexpress.com/item/1005002653014067.html?gatewayAdapt=glo2deu&spm=a2g0o.9042311.0.0.55134c4dMfKc13)
* 4 x Kaihl Hotswap sockets (https://aliexpress.com/item/32951252318.html?gatewayAdapt=glo2deu&spm=a2g0o.9042311.0.0.55134c4dMfKc13)
* 4 x Compatible mechanical switches (Cherry, Kaihl, etc)
* 1 x Atmega32U4 (https://www.digikey.de/de/products/detail/microchip-technology/ATMEGA32U4-AUR/2238241)
* 4 x Diodes (https://www.digikey.de/de/products/detail/taiwan-semiconductor-corporation/1N4148W-G-RHG/7374103)
* 2 x 22 Ohm Resistors (https://www.digikey.de/de/products/detail/stackpole-electronics-inc/RMCF0805JT22R0/1757897)
* 2 x 10k Ohm Resistors (https://www.digikey.de/de/products/detail/stackpole-electronics-inc/RMCF0805JT10K0/1757762)
* 1 x 330 Ohm Resistor (https://www.digikey.de/de/products/detail/stackpole-electronics-inc/RMCF0805FT330R/1760484)
* 2 x 5.1k Ohm Resistor (https://www.digikey.de/de/products/detail/stackpole-electronics-inc/RMCF0805JT5K10/1757930)
* 8 x 0.1uF Capacitors (https://www.digikey.de/de/products/detail/yageo/CC0805ZRY5V9BB104/2103099)
* 1 x 1uF Capacitor (https://www.digikey.de/de/products/detail/yageo/CC0805KKX7R7BB105/2103103)
* 1 x Button (https://www.digikey.de/de/products/detail/e-switch/TL3342F160QG-TR/379003)
* 2 x 22pF Capacitors (https://www.digikey.de/de/products/detail/kemet/C0805C220J5GAC7800/411112)
* 1 x 4.7uF Capacitor (https://www.digikey.de/de/products/detail/murata-electronics/GRM219R61E475KA73D/4905426)
* 1 x 16MHZ Quartz Crystal (https://www.digikey.de/de/products/detail/ecs-inc/ECS-160-18-33-AEN-TR/8023240)
* 1 x USB-C - USB2 Receptacle (https://www.digikey.de/de/products/detail/gct/USB4085-GF-A/9859662)

Thanks to:
* To be able to fit the WS2812B 5050 RGB LEDs i modified the footprints of https://github.com/ai03-2725/MX_Alps_Hybrid
* The creator of the nice silkscreen image.
* QMK Firmware.