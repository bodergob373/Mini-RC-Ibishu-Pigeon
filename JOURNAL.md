---
title: Electric Doohickey
author: Jonathan Itoh
description: A prototype electric vehicle to gain experience and design the electric system of an ethanol-electric hybrid I want to build in the future (and to build a fun go-kart). It's an array of 20 Nissan Leaf batteries managed by a BMS to power a 12kW hub motor (or a temporary hoverboard motor until I could afford it).
created_at: 2025-06-25
---



# June 25th: Research
In order to use one of the 12kW 72V hub motors that I want to use for the full car, I need powerful batteries. I looked at battery cells to buy, but I would need a lot of them. They're expensive and I don't want to wire them all together, so I searched for used EV/hybrid batteries. I found listings for battery modules from both a Toyota Prius and Nissan Leaf. I decided to use the Leaf batteries because they're cheaper and more commonly used.

**Total time spent: 4h**



# June 26th: Research 2
I thought that because they're from a car, maybe I could only use one module with smaller motors. After researching the nominal voltage, I would need more because they're only 8.4V. If I want to keep using the powerful motor, I would need 9 modules. It turns out that their nominal voltage is around 7.2V, so I would actually need 10 in series. The battery also needs to supply enough current for the motor. 12000kW / 72V is 167A, so I will need more battery modules in parallel. I chose to have 4 modules in parallel for the full car with 2 motors, so this kart with only 1 motor should only have 2 in parallel. It's still not enough to run at 12kW continuously, but it could maybe supply enough for a few seconds during acceleration.

**Total time spent: 3h**
