[![cs](https://img.shields.io/badge/lang-cs-red.svg)](README.md)

# PeeWee Rover Light
A simple and affordable PeeWee vehicle for Micro:bit. It is an OpenHardware platform developed to support project-based teaching in subjects such as Programming, Algorithmics, Computational Thinking, and similar.

Without further modifications, the vehicle is designed to be programmed using MakeCode (Blockly / Static TypeScript) with the Micro:bit microcontroller, but it can easily be adapted to any other microcontroller (Arduino, ESP32, etc.).

## About the project
The system is designed with regard to:
- **Mechanical robustness**.
- **Build repeatability:** More expensive components can be reused. Inexpensive items, such as 3D-printed parts and cables, cost only a few dollars. Other students can therefore easily repeat the build from the initial state of disassembled components.
- **Cross-curricular links:** Ideal for connecting disciplines such as polytechnics, algorithmics, electrical engineering, physics, multimedia, mathematics, and more.

## Hardware and construction
The base is a 3D-printed chassis equipped with two DC130 motors with a TT gearbox, two wheels, and a rear trailing caster (a steel ball rotating 360°).

Power is supplied from a 2S 7.4 V battery pack. The L298N motor driver module serves as the power source and motor controller. A Micro:bit connected to an IObit board is used for control logic, making the GPIO connections from the microcontroller easier.

**Lighting (WS2812B):**
A total of 9 addressable RGB LEDs are mounted on the vehicle.
- 5 face backward (B – Back)
- 1 faces left (L – Left)
- 1 faces right (R – Right)
- 2 face forward (F – Front)

The physical order of the LEDs in series is: **F - R - B - B - B - B - B - L - F**

## Schematic and build instructions
- **Simplified electrical wiring schematic:** [schema.svg](schema.svg) (or [schema.pdf](schema.pdf))
- **Build video tutorial:** Due to updates, it is available at the permanent redirect [https://go.pslib.cz/buildpeewee](https://go.pslib.cz/buildpeewee)

## Software / Programming
The control library (extension) for the MakeCode environment is available in the repository:
[https://github.com/microbit-cz/pxt-peewee-light](https://github.com/microbit-cz/pxt-peewee-light)

## Manufacturing data
Data for 3D print: [PeeWeeLight.3mf](model/PeeWeeLight.3mf)

Assembly reference: [PeeWeeLightAssembly.stl](model/PeeWeeLightAssembly.stl)

## Images

![Front view](img/PeeWeeLightFront.jpg)

![Back view](img/PeeWeeLightBack.jpg)

![Prototype photo](img/PeeWeeLight.jpg)

## Parts list

| Quantity | Price | Part | Preview |
|:--------:|------:|------|:-------:|
| 1× | – | [Micro:bit](https://microbit.org/buy/) | ![](img-parts/microbit.webp) |
| 1× | USD 5.75 | [IObit V2.0 expansion board](https://www.aliexpress.com/w/wholesale-microbit-board-IOBIT.html) | ![](img-parts/IObit.webp) |
| 2× | USD 3.32 | [130 DC motor with TT gear 1:48 ratio](https://www.aliexpress.com/w/wholesale-TT-gear-motor.html) | ![](img-parts/TTmotorGear.webp) |
| 2× | USD 1.90 | [65mm yellow wheel](https://www.aliexpress.com/w/wholesale-tt-gear-wheels-65mm.html) | ![](img-parts/wheelYellow.webp) |
| optional 2× | USD 2.20 | [65mm gray 6514 wheel with better adhesion](https://www.aliexpress.com/w/wholesale-6514-wheel.html) | ![](img-parts/wheelGray.webp) |
| 1× | USD 2.80 | [L298N H-bridge motor driver](https://www.aliexpress.com/w/wholesale-L298N-Driver-Board-Module.html) | ![](img-parts/L298N.webp) |
| 1× | USD 1.10 | [18650 2S battery holder](https://www.aliexpress.com/w/wholesale-18650-battery-holder.html) | ![](img-parts/18650box.webp) |
| 2× | USD 5.00 | [18650 battery](https://www.aliexpress.com/w/wholesale-18650-battery.html) | ![](img-parts/LiIon18650.webp) |
| 1× | USD 1.50 | [USB-C 2S BMS charger module](https://www.aliexpress.com/w/wholesale-Type%2525252dC-USB-2S-BMS-15W-charger.html) | ![](img-parts/charger.webp) |
| 1× | USD 0.75 | [steel ball caster wheel](https://www.aliexpress.com/w/wholesale-Vacuum-W420-Steel-Ball-Universal-Wheel.html) | ![](img-parts/ballWheel.webp) |
| 9× | USD 0.50 | [WS2812B LED (60 LED/m, IP30 strip)](https://www.aliexpress.com/w/wholesale-WS2812B-60-LED.html) | ![](img-parts/ws2812b.webp) |
| 15× | USD 0.30 | [Dupont female connectors](https://www.aliexpress.com/w/wholesale-Dupont-2.54mm-TJC8%2525252dT%2525252dD.html) | ![](img-parts/dupontfemale.webp) |
| 2× | USD 0.05 | [Dupont 4PIN plastic housing 2.54mm](https://www.aliexpress.com/w/wholesale-Dupont-4PIN-plastic-housing-2.54mm.html) | ![](img-parts/default.webp) |
| 1× | USD 0.02 | [Dupont 2PIN plastic housing 2.54mm](https://www.aliexpress.com/w/wholesale-Dupont-2PIN-plastic-housing-2.54mm.html) | ![](img-parts/default.webp) |
| 1× | USD 0.50 | [20cm servo extension cable](https://www.aliexpress.com/w/wholesale-20cm-Servo-Extension-Cable-30-core.html) | ![](img-parts/default.webp) |
| – | USD 0.70 | [37cm 26AWG silicone servo wire](https://www.aliexpress.com/w/wholesale-servo-cable-wire-26AWG-30-Core.html) | ![](img-parts/default.webp) |
| – | USD 0.25 | [20cm 20AWG 2PINs silicone wire](https://www.aliexpress.com/w/wholesale-20cm-20AWG-Silicone-Wire.html) | ![](img-parts/default.webp) |
| 1× | USD 0.50 | [Micro-USB Male 2Pin with Welding Wire](https://www.aliexpress.com/w/wholesale-Micro-USB-Male-JACK-2Pin-Welding-Wire.html) | ![](img-parts/default.webp) |
| 1× | USD 0.25 | [20mm snap-in round rocker switch](https://www.aliexpress.com/w/wholesale-round-snap%2525252din-mini-Rocker-Switch.html) | ![](img-parts/switch.webp) |
| 6× | USD 0.10 | [3×100mm self-locking zip ties](https://www.aliexpress.com/w/wholesale-Self%2525252dLocking-Zip-Ties-3x100.html) | ![](img-parts/default.webp) |
| – | USD 0.10 | [heat-shrink tubing 2mm/3mm](https://www.aliexpress.com/w/wholesale-heatshrink-tube.html) | ![](img-parts/default.webp) |
| 6× | USD 0.20 | [M3×6mm screws PH DIN 7985](https://eshop.killich.cz/detail/sroub-m3x6-zinek-4-8-pulkulata-hlava-krizova-drazka-ph-din-7985) | ![](img-parts/default.webp) |
| 6× | USD 0.20 | [plastic self-tapping screw 2.2×5mm](https://eshop.killich.cz/detail/sroub-do-plastu-2-2x5-f-zinek-pulkulata-hlava-krizova-drazka-pz-tupy-plasfast-30) | ![](img-parts/default.webp) |

*Total cost:* USD 27.99 (excluding micro:bit and 3D printing parts)