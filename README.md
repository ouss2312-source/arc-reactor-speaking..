# arc-reactor-speaking..
DIY bluetooth speaker with mounted arc reactor style, includes led theme as speaker screaming.


# Arc Reactor Bluetooth Speaker

> "Proof that Tony Stark has a heart." — and now, proof that we can build one.

A DIY 360° Bluetooth speaker with a custom Arc Reactor mounted at the center. Built as a hardware project.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c58b69a0-6b43-49a9-a9db-ab7b74b8a190" />

---

## What it does

- Plays audio wirelessly over Bluetooth 5.0
- Four full-range drivers arranged at N/S/E/W for 360° sound
- Arc Reactor centerpiece with animated WS2812B LED ring (prob. blue breathing pulse)
- Rechargeable
- All electronics arranged around the reactor mount

---

## Parts list

| Part | Spec | Qty |
|---|---|---|
| 18650 Li-ion cells | 3.7V, 2500mAh+ | 2 |
| BMS module | 4S, 5A protection | 1 |
| DC 5.5 mm | 16.8V input | 1 |
| DC adaptor 16.6V | Charge battery | 1 |
| Amplifier board | TDA7388 (12V) | 1 |
| Full-range speaker driver | 2–3 inch, 4Ω | 4 |
| WS2812B LED ring | ~60mm, 16 LEDs | 1 |
| ESP32 | For LED control and bluetooth | 1 |
| Power button | Momentary or latching | 1 |
| Enclosure | Circular, 3D printed or custom | 1 |
| LM2596 Buck Converter | 14.8V → 5V | 1 |

---

## Schematic

See [`docs/schematic.md`](docs/schematic.md) for the full wiring diagram.

- Power chain: Battery → BMS → Amp
- Audio chain: ESP32 → Amp → 4× drivers
- LED chain: ESP32 → WS2812B ring (mounted on Arc Reactor face)

---

## Build sessions

| Session | Topic | Status |
|---|---|---|
| 1 | Read schematic, order parts | ⬜ |
| 2 | Power circuit — battery, BMS, boost | ⬜ |
| 3 | Audio chain — BT module, amp, drivers | ⬜ |
| 4 | Arc Reactor LED ring + enclosure | ⬜ |
| 5 | Final assembly + Hack Club submission | ⬜ |

---
