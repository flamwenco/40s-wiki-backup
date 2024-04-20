---
title: QAZ
description: QAZ Keyboard by CBKBD
published: true
date: 2024-04-20T19:55:06.167Z
tags: row stagger, qaz
editor: markdown
dateCreated: 2023-02-08T20:41:09.610Z
---

# QAZ

QAZ is a 35% keyboard, designed by tominabox1 and whydobearsxplod.

### Overview

The QAZ is a 4u x 10.25u keyboard. The original version of the QAZ was Pro Micro based, but subsequent revisions of it have an integrated microcontroller (ATM 32u4 or RP2040). 

![qaz.jpeg](/boards/images/qaz.jpeg){.align-right}

### Variants & Layout

The QAZ PCB, with few exceptions, is only sold as a PCB; there is no "standard" case to go with it like exists for some other keyboard PCBs. There have been few different variants developed and all variants produced have kept the same layout support for 4 1u bottom row keys and a 6.25u space bar or 6 1u bottom row keys and a 2.25u and 2.0u split bar bottom row. 

The first variant of the QAZ PCB utilized a Pro Micro microcontroller. This required either the switch above the pro micro to be soldered in first before the Pro Micro or that the Pro Micro Be socketed. 

Subsequent revisions of the QAZ PCB replaced the Pro Micro with an integrated ATM 32u4 MCU. The switch the was above where the Pro Micro would reside on previous PCBs was now rotate 180° to make space for an integrated USB C port on the PCB. 

A limited amount of QAZ PCBs that supported Gateron KS-33 switches (but were otherwise the same) were produced but never remained as an in stock item, likely due to issues with switch alignment, and keycap compatibility issues with KS-33 switches.

A KLE of the QAZ PCB is available [here](http://www.keyboard-layout-editor.com/##@@=Q%0A1u&=W&=E&=R&=T&=Y&=U&=I&=O&_w:1.25%3B&=P%0A1.25u%3B&@_w:1.25%3B&=A%0A1.25u&=S&=D&=F&=G&=H&=J&=K&=L&=Enter%0A1u%3B&@_w:1.75%3B&=Z%0A1.75u&=X&=C&=V&=B&=N&=M&=%3C%0A.&_w:1.5%3B&=Shift%0A1.5u%3B&@_c=%23f7baba%3B&=Super%0A1u&=Meta%0A1u&_w:6.25%3B&=%0A6.25u&=Meta%0A1u&=Super%0A1u%3B&@_y:1%3B&=%0A1u&=%0A1u&=%0A1u&_w:2.25%3B&=%0A2.25u&_w:2%3B&=%0A2u&=%0A1u&=%0A1u&=%0A1u).

### Case Options

There are a variety of third party case options. This list is incomplete and additions are welcome.

* A case called the "Qull" (a hull mount QAZ case) was sold on CBKBD's website at one point
* The Brane Minus kit from CBKBD utilizes a QAZ PCB
*   [P3D Acrylic Case](https://p3dstore.com/collections/acrylic-keyboard-cases/products/qaz-acrylic-keyboard-case)
*   [P3D 3D Printed Case](https://p3dstore.com/collections/3d-printed-keyboard-cases/products/qaz-3dp-keyboard-case)
*   [QAZKET](https://crft.bigcartel.com/product/qazket)
*   [QAZ-Simple](https://github.com/dingusxmcgee/QAZ-Simple) (BriefQAZ is this but with a handle)
*   [QAZ-Tilt](https://github.com/dingusxmcgee/QAZ-Tilt)
*   [QAZ MFR2](https://github.com/seirin-blu/QAZ-MFR2) (A mfr2-styled QAZ case)

### Availability

QAZ is closed source. PCBs are available at [Coffee Break Keyboards](https://www.cbkbd.com/product/qaz-keyboard-kit).