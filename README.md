# Almost-free-cooling-system
Cooling system (home or factory) COP > 50 / COP > 150 / Theoretically COP = ∞


Passive Cooling System Using Evaporation/Condensation and EHD or Venturi-Driven Airflow

Overview

This document describes a passive cooling system that uses water's phase change (evaporation and condensation) and air movement driven either by Venturi geometry or electrohydrodynamic (EHD) ion wind propulsion. It is designed to operate without traditional compressors or refrigerant gases, offering extremely high energy efficiency.


---

Operating Parameters

Interior target temperature: 26 °C

Water (working fluid) evaporation temperature: 26 °C

Condensation temperature at the Venturi neck: 21 °C

Exterior ambient temperatures tested: 30 °C, 35 °C, 40 °C



---

Thermodynamic Principles

Latent Heat of Vaporization for Water:

Q = m \cdot L

: heat transferred (J)

: mass of water (kg)

: latent heat of vaporization (~2.26 MJ/kg)


Cooling Capacity:

To cool a 50 m² home at ~100 frig/h/m²:

5000 \, \text{frig/h} = 5813.89 \, \text{W}

Mass Flow Required:

m = \frac{Q}{L} = \frac{5813.89}{2.26 \times 10^6} = 0.00257 \text{ kg/s} = 9.26 \text{ kg/h}


---

Evaporation and Condensation Pressures

Using Antoine's Equation:

\log_{10}(P) = A - \frac{B}{C + T}

A = 8.07131

B = 1730.63

C = 233.426


At 26 °C (Evaporation):

P \approx 33.7 \, \text{mbar}

At 21 °C (Condensation):

P \approx 24.8 \, \text{mbar}


---

Venturi Geometry

Throat air velocity: 100 m/s (estimated)

Throat diameter: 1.4 cm

Throat length: 9.7 cm


Each Venturi nozzle includes a copper microtube coil (1 mm inner diameter, 33 cm long) wrapped around a 9 mm cylinder to condense vapor efficiently with minimal air resistance.


---

Interior Heat Exchanger

Total heat to extract: 5813.89 W

Temperature gradient: 5 °C

Natural convection (U = 35 W/m²·K):


A = \frac{Q}{U \cdot \Delta T} = \frac{5813.89}{35 \cdot 5} \approx 33.22 \, \text{m}^2

Effective exchange area per meter of tubing: ~0.942 m²

Total copper tube length: ~35.2 m

COP and Efficiency Considerations

The proposed cooling system is a fully passive solution that operates using only a minimal low-power pump (0.05 W) powered by a small solar panel. Under standard operating conditions, this configuration enables the system to remove approximately 5813.89 W of thermal energy with only 0.05 W of electrical input. This results in a theoretical COP (Coefficient of Performance) of:

COP = \frac{5813.89}{0.05} = 116,278

If solar energy is considered "free," the system can be interpreted as having a COP approaching infinity, since it performs mechanical work without conventional energy input.

Optional Forced Ventilation

The system can optionally incorporate forced airflow to reduce the size of internal and external components:

1. Conventional Fan Ventilation

Power consumption: 38 W

Cooling power maintained: 5813.89 W

Resulting COP:


COP = \frac{5813.89}{38 + 0.05} \approx 153.6

2. Electrohydrodynamic (EHD) Ion Wind Ventilation

Power consumption: 40 W

Cooling power maintained: 5813.89 W

Resulting COP:


COP = \frac{5813.89}{40 + 0.05} \approx 145.2

Summary

The base system (passive + solar-powered pump) achieves a COP > 116,000. Or COP = ∞ considering solar as "free energy"

Adding forced ventilation significantly reduces the required physical size of heat exchangers and condensers, with a modest decrease in COP:

~153.6 with conventional fans

~145.2 with EHD ion wind modules



This tradeoff allows design flexibility depending on space constraints and budget.



---

EHD Ion Wind Cooling (Night Mode)

Total electric input: 10 W (0.5 W per nozzle)

Airflow generated: 1.75 m³/h per nozzle → 35 m³/h total

Cooling capacity: ~251 W (via 0.4 L/h of condensation)

Resulting COP:


COP = \frac{251}{10} = 25.1


---

Licensing

Copyright 2024 - Passive EHD Cooling Project
All rights reserved.
This concept, calculations, and system design are protected under a custom license.

Commercial use, reproduction, or modification of this concept is prohibited without explicit written permission from the author.

For licensing inquiries, please contact the project owner.

Simple Explanation of the Passive Cooling System

This is a new kind of cooling system that works without gas refrigerants, compressors, or electricity (except a tiny solar-powered pump). It uses natural forces like air pressure, sun heat, and water evaporation to cool a house in a very efficient way.


---

How it works (in simple words):

1. Interior Unit (Evaporator)

Inside the house, there is a small unit filled with water.

The room is at 26 °C.

At this temperature, the water turns into vapor (gas) and takes away heat from the room, just like sweat cools your skin.


2. Gas Transport (Passive)

The vapor naturally moves towards the outside unit because gas always moves from high to low pressure.

No electricity is needed to move the gas, only a small pump to return the liquid later (only a few watts).


3. Exterior Unit (Condenser with Venturi)

Outside the house, there is a vertical tube heated by the sun. This creates a chimney effect: hot air goes up.

The air flows through a narrow neck called a Venturi.

In that Venturi, the air moves faster, and the temperature drops to around 21 °C.

At that point, the vapor turns back into water (condensation).


4. Liquid Return

The liquid water from the condenser returns to the interior unit using gravity or a tiny pump.

Once inside, the cycle starts again: the water evaporates, cools the house, and the vapor travels out to condense again.



---

Why it's efficient

It works using the natural heat of the sun and temperature differences.

The only power needed is for a small pump (1–2 watts).

You can power it with a small solar panel.

Since it moves 5,000–6,000 watts of heat using almost no electricity, the COP (efficiency) can be 150 or more, and theoretically infinite if powered entirely by sunlight.



---

Summary

It’s a clean, quiet, and ultra-efficient cooling system that works like nature:

Heat makes water evaporate

Air pressure moves the vapor

Fast air cools it down again

The cycle runs almost for free




---

📜 License and Contribution Notice

This idea and its description, as published here, are protected under a Creative Commons Attribution-NonCommercial (CC BY-NC) license.

🛠 DIY / Maker-friendly:
Everyone is welcome to use, replicate, and improve upon this idea for personal, educational, or non-commercial purposes. Feel free to share your results, photos, prototypes, and tests directly within this repository or as linked contributions.

💼 Commercial Use Prohibited Without Permission:
Any commercial use of this idea, in part or in full, requires explicit permission from the original author.

🤝 Community & Merit-Based Rewards:
If this project eventually receives any form of economic return, I (the author) will personally ensure that collaborators are compensated according to their level of contribution, in a way I deem fair and meritocratic.

Thank you for building, sharing, and respecting the spirit of open, ethical innovation.
— Pol Barreiro Font




