# BOM — WPT Drone Wireless Charger
# Based on: Srivastava et al. (IIT Ropar, 2025)
# System: SS Topology | 100kHz | 7.4V 2S LiPo 2200mAh

---

## COMMON COMPONENTS

| # | Component | Part | Qty | Rate ₹ | Amount ₹ |
|---|---|---|---|---|---|
| 1 | MOSFET | IRF540N | 4 | 35 | 140 |
| 2 | Gate driver | IR2110 | 2 | 60 | 120 |
| 3 | Microcontroller | Arduino Nano | 1 | 180 | 180 |
| 4 | Bootstrap cap | 100nF ceramic | 2 | 10 | 20 |
| 5 | Bootstrap diode | 1N4007 | 2 | 5 | 10 |
| 6 | Gate resistor | 10Ω 0.5W | 4 | 5 | 20 |
| 7 | DC bus cap | 100µF 25V electrolytic | 2 | 10 | 20 |
| 8 | Decoupling cap | 100nF ceramic | 4 | 5 | 20 |
| 9 | Tx resonance cap Cp | 270pF C0G 1kV | 1 | 40 | 40 |
| 10 | Rx resonance cap Cs | 270pF C0G 1kV | 1 | 40 | 40 |
| 11 | Litz wire Tx coil | 40AWG 25 strand 1.5m | 1 | 150 | 150 |
| 12 | Litz wire Rx coil | 40AWG 25 strand 1m | 1 | 100 | 100 |
| 13 | Rectifier diode | SB540 | 4 | 20 | 80 |
| 14 | Filter cap | 100µF 25V electrolytic | 1 | 10 | 10 |
| 15 | 2S BMS module | 2S 10A BMS | 1 | 90 | 90 |
| 16 | Battery | 7.4V 2S LiPo 2200mAh | 1 | 800 | 800 |
| 17 | Test resistor | 10Ω 5W wirewound | 1 | 15 | 15 |
| 18 | Coil base Tx | Thermocol 250x250mm | 1 | 20 | 20 |
| 19 | Coil base Rx | Thermocol 150x150mm | 1 | 20 | 20 |
| 20 | Breadboard | 830 points large | 2 | 80 | 160 |
| 21 | Jumper wires | Assorted M-M M-F | 1 set | 60 | 60 |
| 22 | Multimeter | Basic digital | 1 | 300 | 300 |
| **TOTAL** | | | | | **2,415** |

---

## BUCK — OPTION A (Scratch)

| # | Component | Part | Qty | Rate ₹ | Amount ₹ |
|---|---|---|---|---|---|
| 1 | Buck MOSFET | IRF540N | 1 | 35 | 35 |
| 2 | Freewheeling diode | SB540 | 1 | 20 | 20 |
| 3 | Buck inductor | 100µH 3A | 1 | 80 | 80 |
| 4 | Buck output cap | 22µF 25V ceramic | 1 | 20 | 20 |
| 5 | Buck input cap | 100µF 25V electrolytic | 1 | 10 | 10 |
| 6 | Arduino Nano | Arduino Nano | 1 | 180 | 180 |
| 7 | Gate resistor | 10Ω 0.5W | 1 | 5 | 5 |
| 8 | Pull down resistor | 10kΩ | 1 | 5 | 5 |
| **TOTAL** | | | | | **355** |

---

## BUCK — OPTION B (LM2596 IC — as used in Paper)

| # | Component | Part | Qty | Rate ₹ | Amount ₹ |
|---|---|---|---|---|---|
| 1 | Buck regulator IC | LM2596-ADJ | 1 | 50 | 50 |
| 2 | Freewheeling diode | SB540 | 1 | 20 | 20 |
| 3 | Buck inductor | 100µH 3A | 1 | 80 | 80 |
| 4 | Output cap | 220µF 25V electrolytic | 1 | 15 | 15 |
| 5 | Input cap | 100µF 25V electrolytic | 1 | 10 | 10 |
| 6 | Resistor R1 | 1kΩ 0.25W | 1 | 5 | 5 |
| 7 | Resistor R2 | 5.6kΩ 0.25W | 1 | 5 | 5 |
| 8 | Decoupling cap | 100nF ceramic | 1 | 5 | 5 |
| **TOTAL** | | | | | **190** |

---

## COST SUMMARY

| | Common ₹ | Buck ₹ | Total ₹ | With 10% buffer ₹ |
|---|---|---|---|---|
| **Option A — Scratch buck** | 2,415 | 355 | 2,770 | **~3,047** |
| **Option B — LM2596 IC buck** | 2,415 | 190 | 2,605 | **~2,866** |

