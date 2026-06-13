# Stargate Parts List & Links (V2.1.3)

> I have no idea if the links listed here will work, if the parts are from a reliable vendor or if they are of good quality. Please do your own research.

## Modules & Major Parts

| Reference | Qty | Value | Link example |
|---|---|---|---|
| Fuse | 1 | 1.5A | <https://www.aliexpress.us/item/2255801012350097.html> |
| Fuse | 1 | 0.5A | <https://www.aliexpress.us/item/2255801012350097.html> |
| Relay | 1 | HFD4-5 | <https://www.aliexpress.us/item/3256806642059309.html> |
| OLED Screen | 1 | SSD1306 128x32 | <https://www.aliexpress.us/item/3256810382441111.html> |
| DIN8 | 1 | 8 pins | <https://www.aliexpress.us/item/3256803009734845.html> |
| OVP | 1 | Overvoltage Protection 5V | <https://www.aliexpress.us/item/3256810199010529.html> |
| Clock Gen | 1 | SI5351 | <https://www.aliexpress.us/item/3256809498025225.html> |
| YM2149F | 1 | Yamaha audio chip (AY-3-8910 was not tested) | <https://www.aliexpress.us/item/3256805857392394.html> |
| 3.57MHz | 1 | oscilator module xtal | <https://www.aliexpress.us/item/2251832699611090.html> |
| dd1718pa | 1 | Buck module +-12V (NO PIN option) | <https://www.aliexpress.us/item/3256807659398693.html> |
| RGB strip | 1 | 5V (2.7mm), 1m | <https://www.aliexpress.us/item/3256806542970058.html> |
| Amplifier | 1 | Onboard Amp 5128 | <https://www.aliexpress.us/item/3256807058360209.html> |
| Potentiometer | 1 | Potentiomenter 47K/50K (mono or stereo) | <https://www.aliexpress.us/item/2251832675872559.html> |
| Tactile Switch angle | 3 | 6x6x15 (3 - back buttons) | <https://www.aliexpress.us/item/3256809907015472.html> |
| Tactile Switch | 3 | 6x6x13 (3 - oled buttons) | <https://www.aliexpress.us/item/3256805862813072.html> |
| Tactile Switch | 2 | 6x6x4.3 (2 - ESP buttons) | <https://www.aliexpress.us/item/3256805862813072.html> |
| MCU | 1 | ESP12F (the older ESP12E also works) | <https://www.aliexpress.us/item/3256805905748177.html> |
| ams1117-3v3 | 1 | 3.3V regulator SMD | <https://www.aliexpress.us/item/3256802301389307.html> |
| ON/OFF | 1 | switch (15x21) | <https://www.aliexpress.us/item/3256807758713102.html> |
| PC817 | 1 | optocoupler | <https://www.aliexpress.us/item/3256808061802481.html> |
| Micro SD flex | 1 | Extension 25cm | <https://www.aliexpress.us/item/3256806940297869.html> |
| M18 BT | 1 | BT Module | <https://www.aliexpress.us/item/3256809630730449.html> |

### Others

| Reference | Value | Link example |
|---|---|---|
| Keycaps set | Option "Black JIS" (two horizontal ENTER keys) | <https://www.aliexpress.us/item/3256809277322870.html> |
| Keycaps set | Japanese Option | <https://www.aliexpress.us/item/3256806285170564.html> |
| Keyboard stabilizers | 4 pieces (clip-on) | <https://www.aliexpress.us/item/3256801500004993.html> |
| Keyboard stabilizers | 4 pieces (with screws, safer) - black color | <https://www.aliexpress.us/item/3256807050530252.html> |
| Switches kit | MX 5 pins | |
| Switches caps | mixed colors | <https://www.aliexpress.us/item/3256809614465685.html> |

## Passive Components

- **Resistors:** 1/4W
- **Capacitors:** C5–C6 ≥ 25V and the rest is ≥ 16V

| Reference | Qty | Value | Footprint |
|---|---|---|---|
| C1, C2, C3 | 3 | DNP | NA |
| C4 | 1 | 470uF | Capacitor Electrolytic: lead space 5mm / Height: <10mm |
| C5, C6 | 2 | 220uF | Capacitor Electrolytic: lead space 3.5mm / Height: <10mm |
| C7, C8, C9, C10, C11, C12, C15, C16, C18, C20, C21, C22, C23, C24, C25, C26, C27, C28, C29, C30, C36, C43, C44, C45, C46, C52, C57, C58, C31, C32, C33, C34, C35 | 28 | 100nF | Capacitor Tantalum or Multilayer: lead space 5mm |
| C13, C14, C42 | 3 | DNP | NA |
| C17 | 1 | 220uF | Capacitor Electrolytic: lead space 2.5mm / Height: <8mm |
| C19, C37, C38, C39, C40, C41, C47, C50, C51, C54, C55, C59 | 12 | 10uF | Capacitor Electrolytic: lead space 2.5mm / Height: <8mm |
| C48, C49 | 2 | 22nF | Capacitor Tantalum or Multilayer: lead space 2.5mm |
| C53 | 1 | up to 22nF | Capacitor Tantalum or Multilayer: lead space 5mm (internal amp - high frequency cut) |
| C56 | 1 | DNP | - |
| R1, R13, R42, R43, R34, R35, R36, R41 | 4 | 470R | Resistor 1/4w 7.62mm_Horizontal |
| R2, R3, R4, R5, R6, R7, R18, R22, R27, R28, R29, R30, R31, R32, R39, R44 | 16 | 10K | Resistor 1/4w 7.62mm_Horizontal |
| R8, R9, R15, R16, R23, R26 | 6 | 4K7 | Resistor 1/4w 7.62mm_Horizontal |
| R10, R11 | 2 | 20K | Resistor 1/4w 7.62mm_Horizontal |
| R12 | 1 | 2K2 | Resistor 1/4w 7.62mm_Horizontal |
| R14, R25, R40 | 3 | 1K | Resistor 1/4w 7.62mm_Horizontal |
| R17 | 1 | 100R | Resistor 1/4w 7.62mm_Horizontal |
| R19 | 1 | 470K | Resistor 1/4w 7.62mm_Horizontal |
| R20, R21 | 2 | 2K7 | Resistor 1/4w 7.62mm_Horizontal |
| R24 | 1 | 220K | Resistor 1/4w 7.62mm_Horizontal |
| R26 | 1 | 18K | Resistor 1/4w 7.62mm_Horizontal |
| R33 | 1 | 3K3 | Resistor 1/4w 7.62mm_Horizontal |
| R34, R35, R36, R41 | 4 | 470R | Resistor 1/4w 7.62mm_Horizontal |
| R37 | 1 | 220R | Resistor 1/4w 7.62mm_Horizontal |
| R38 | 1 | 1M | Resistor 1/4w 7.62mm_Horizontal |

## Integrated Circuits

| IC Reference | Qty | Value | Alternates |
|---|---|---|---|
| U1 | 1 | AMS1117-3.3 | LM1117-3.3 |
| U10 | 1 | 74HC139 | LS/HCT |
| U11 | 1 | 74HC153 | LS/HCT |
| U12 | 1 | 74HC02 | LS/HCT |
| U13, U16 | 2 | 74LVC245 | - |
| U14, U15 | 2 | 74HC373 | HCT |
| U17 | 1 | Tang_Nano_20k | NA |
| U18 | 1 | 74HC245 | - |
| U19 | 1 | YM2149 | |
| U2, U4 | 2 | 74HC74 | LS/HCT |
| U20, U26 | 2 | 74LS07 | - |
| U21, U22 | 2 | 74HC157 | LS/HCT |
| U23 | 1 | LM311 | P or N |
| U24 | 1 | ESP-12F | |
| U25 | 1 | PC817 | |
| U27 | 1 | 74LS145 | - |
| U3 | 1 | TL7705A | |
| U5 | 1 | 8255 | |
| U6 | 1 | 74HC138 | LS/HCT |
| U7 | 1 | 74HC08 | LS/HCT |
| U8 | 1 | 74HC32 | LS/HCT |
| U9 | 1 | 74HC00 | LS/HCT |

## Powering Your Stargate

USB-C or Barrel Jack (**USB-C HIGHLY recommended**).

### Barrel Jack option

> A low quality power supply can cause freezes and other unknown behaviours.

| Reference | Value | Link example |
|---|---|---|
| Jack connector | Barrel jack 5.5mm (with 2.1mm hole) | <https://www.aliexpress.us/item/3256803142763786.html> |
| Power adaptor | 5V-2A (3A recommended) 5.5mm / center positive (with 2.1mm hole) | <https://www.aliexpress.us/item/3256803596239663.html> |
| Power adaptor (alt) | — | <https://www.aliexpress.us/item/3256808282333732.html> |
| Power adaptor (alt) | — | <https://www.aliexpress.us/item/3256808943863317.html> |

### USB-C option

| Reference | Value | Link example |
|---|---|---|
| USB-C power brick | >10W (2A) [15W (3A) recommended] any type is ok (common or PD) | Try your phone charger |
| USB-C power | USB Decoy (or barrel jack optional) | <https://www.aliexpress.us/item/3256808182904772.html> |
