<div align="center">

# 🩺 Pulse Oximeter & OLED Interface
### Complete PCB Design for Arduino Nano & MAX30102

[![KiCad](https://img.shields.io/badge/KiCad-8.0-blue?logo=kicad&logoColor=white)](https://www.kicad.org/)
[![Arduino](https://img.shields.io/badge/Arduino-Nano_v3-00979D?logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

*Kompaktowy, dwuwarstwowy moduł PCB pulsooksymetru zintegrowany z wyświetlaczem OLED oraz przyciskami sterującymi.*

</div>

---

## 📸 Podgląd projektu

| Widok 3D (Front) | Widok 3D (Back) |
| :---: | :---: |
| ![Front 3D](docs/front.png) | ![Back 3D](docs/back.png) |

---

## 🛠️ Specyfikacja techniczna

* **Mikrokontroler:** Arduino Nano v3 (ATmega328P)
* **Czujnik tętna i SpO2:** MAX30102 (I2C)
* **Wyświetlacz:** OLED 0.96" SSD1306 / 128x64 px (I2C)
* **Interfejs użytkownika:** 3x przyciski Tact Switch ze sprzętową filtracją drgań styków (RC)
* **Wymiary PCB:** 2-warstwowa płyta FR4 (grubość $1.6\text{ mm}$)
* **Zasilanie:** 5V z portu USB Arduino Nano

---

## 🗂️ Struktura repozytorium

```text
.
├── docs/           # Wyrenderowane zdjęcia 3D projektu
├── gerber/         # Paczka produkcyjna (gerber.zip) gotowa do zamówienia
└── hardware/       # Pliki źródłowe KiCad (.kicad_pcb, .kicad_sch, .kicad_pro)
