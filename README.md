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
- Rechargeable via USB-C
- All electronics arranged radially around the reactor mount

---

## Parts list

| Part | Spec | Qty |
|---|---|---|
| 18650 Li-ion cells | 3.7V, 2500mAh+ | 2 |
| BMS module | 2S, 5A protection | 1 |
| Boost converter | 3.7V → 5V/12V | 1 |
| USB-C charge module | 5V input | 1 |
| Bluetooth audio module | BT 5.0, XY-BT-Mini or similar | 1 |
| Amplifier board | PAM8403 (5V) or TPA3116 (12V) | 1 |
| Full-range speaker driver | 2–3 inch, 4Ω or 8Ω | 4 |
| WS2812B LED ring | 60mm, 12 or 16 LEDs | 1 |
| Arduino Nano / ATtiny85 | For LED control | 1 |
| Power button | Momentary or latching | 1 |
| Enclosure | Circular, 3D printed or custom | 1 |

---

## Schematic

See [`docs/schematic.md`](docs/schematic.md) for the full wiring diagram.

- Power chain: Battery → BMS → Boost converter → Amp
- Audio chain: BT module → Amp → 4× drivers
- LED chain: Arduino → WS2812B ring (mounted on Arc Reactor face)

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
