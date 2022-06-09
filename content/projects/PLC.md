---
title: "Create Ladder Logic Based on Problems"
date: "2022-03-30"
author: "Stephanie Zepeda"
cover: "img/plc.jfif"
description: "The solution of a problem using a PLC and pneumatic systems."
---

An automotive air bag inflator cup is loaded into the part nest of the press machine. the operator places a 'cap' over the inflator cup, then presses a star button (PB1). The part is then "clamped" in the nest by a double acting cylinder to secure it. Once clamped (PX1), a light turns on (LT1) indicating the part is ready to be pressed. once clamped (LT1), the operator then presses 2 pushbuttons simultaneously (PB2 & PB3) to advance the press cylinder. The single acting press cylinder moves forward very slowly and hold its pressed condition for 3 seconds when cylinder moves forward position (PX2). Once 3 seconds have elapsed, the press cylinder automatically returns, and the clamp cylinder unclamps the part once the operator releases either control button. the BCD light counter (LT2-4) will increment by 1. when the counter has updated and the operator has released both buttons, the operator can then press another part. after 7 parts have been counted, and the operator has released both PB's, the counter must reset to "0".

{{< image src="/img/plc1.png" alt="Clamp and Press Machine Tag List" position="center" style="border-radius: 8px;" >}}

{{< image src="/img/plc2.png" alt="Clamp and Press Machine Pneumatic Schematic" position="center" style="border-radius: 8px;" >}}

{{< image src="/img/plc3.png" alt="Clamp and Press Machine Electrical Schematic" position="center" style="border-radius: 8px;" >}}
