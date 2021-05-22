This is Pill 60, it offers various bottom row layout, a stepped caps, an OLED screen, and two rotary encoder, and uses Kailh Hotswap Socket, and underglow RGB LED.

layout is [this](http://www.keyboard-layout-editor.com/##@_name=Pill60&author=IktaS%3B&@_a:7&f:7%3B&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&_c=%2300ffdd%3B&=1&=1%3B&@_c=%23cccccc&w:1.5%3B&=1.5&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&_c=%2300cc55&w:1.5%3B&=1.5%3B&@_c=%2350d38a&w:1.75%3B&=1.75&_c=%23cccccc%3B&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&_c=%2300cc55&w:2.25%3B&=2.25%3B&@_c=%23aaaacc&w:2.25%3B&=2.25&_c=%23cccccc%3B&=1&=1&=1&=1&=1&=1&=1&=1&=1&=1&_c=%23cc77cc&w:1.75%3B&=1.75&=1%3B&@_c=%23995555&w:1.25%3B&=1.25&_w:1.25%3B&=1.25&_w:1.25%3B&=1.25&_c=%23889988&w:6.25%3B&=6.25&_c=%23558899&w:1.25%3B&=1.25&_w:1.25%3B&=1.25&_w:1.25%3B&=1.25&_w:1.25%3B&=1.25%3B&@_c=%23b3ce29&w:1.5%3B&=1.5&=1&_w:1.5%3B&=1.5&_c=%23939393&w:6%3B&=6&_c=%23558899&w:1.5%3B&=1.5&=1&=1&_w:1.5%3B&=1.5&_x:0.5&c=%2350d38a&w:1.25&w2:1.75&l:true%3B&=1.75)

This 60% keyboard that uses BluePill or STM32F103C8T6.This is my first board, Any feedback is appreciated. Contact me on Discord Ikta#8871.

## Firmware
Firmware is currently waiting for merge to QMK Firmware Repository, but you can still access it from my [fork](https://github.com/IktaS/qmk_firmware/tree/pill60/keyboards/handwired/pill60)

## Update
Modified the pinout diagram so that it doesn't crash with Black Pill or STM32F4xxx line of board, the pinout obviously will be different, but because all uses the a valid pin even with Black Pill / Blue Pill configuration, pin matrix diagram can be modified in firmware level.

## Caution
You might need to use a jumper for a more reliable connector in the caps/control key. I guess the pad is a bit too small for it to keep holding on with constant pressure of being pressed hard.

![Front Side view](./images/FrontSide.png)
![Back Side view](./images/BackSide.png)
![Wire view](./images/Wires.png)
![PCB Front view](./images/PCBFront.png)
![PCB Back view](./images/PCBBack.png)
