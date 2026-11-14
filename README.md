# ATtiny85 Programmer

This is a programmer for ATtiny85 microcontrollers. It uses an Arduino Nano and a custom PCB. With it, you can easily program the ATtiny85 for projects such as [Tiny Tetris](https://github.com/lonesoulsurfer/Tiny_Tetris) and [Tiny Arcade](https://github.com/lonesoulsurfer/Tiny_Arcade_Games).

![ATtiny85 Programmer](https://github.com/user-attachments/assets/731d9ab6-fcc2-432f-b610-fa665e0e3240)

It is for beginners and for experienced users.

## Build guide and video

- Step-by-step build guide on Instructables, with the parts list: [Programmer for ATtiny 85](https://www.instructables.com/Programmer-for-ATtiny-85/)
- Video on YouTube, with the build and how to program an ATtiny85: [ATtiny85 Programmer](https://www.youtube.com/watch?v=726uLVw5450)

## What you need

### Hardware

- The parts list is in the [Instructables guide](https://www.instructables.com/Programmer-for-ATtiny-85/).
- The schematic is [schematic.png](schematic.png).
- The Gerber files for the PCB are in [Gerber File](Gerber%20File/). You can send them to a PCB maker.
- An Arduino Nano

### Software

- Arduino IDE

## How to use it

The Instructables guide and the video show each step. In short:

1. Upload the **ArduinoISP** example sketch to the Arduino Nano. In the Arduino IDE, click **File → Examples → 11.ArduinoISP → ArduinoISP**, then click **Upload**.
2. Put the Nano and the ATtiny85 on the programmer PCB.
3. Install ATtiny support in the Arduino IDE, as the guide tells you.
4. Open the sketch that you want to put on the ATtiny85.
5. Set **Programmer** to **Arduino as ISP**.
6. Click **Sketch → Upload Using Programmer**.

To test the programmer, use the `blink_sketch` in this repository. It makes an LED flash.

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `Eagle Files/` | Eagle files for the PCB |
| `Gerber File/` | Gerber files for the PCB, ready to order |
| `blink_sketch/` | A test sketch that makes an LED flash |
| `schematic.png` | Schematic |

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

This project uses the [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0). Copyright (c) 2024 Marcus (lonesoulsurfer).

You can make, change and sell boards from these files. If you share or sell a changed design, you must also share the changed design files under the same licence.
