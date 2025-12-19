---
layout: project
title: Two-Stage Solid Rocket (100 mm Diameter)
description: High-performance two-stage solid rocket with custom composite airframe, autonomous staging avionics, and 17,718 ft precision flight result.
technologies:
  - Composite Structures (Fiberglass / Carbon Fiber)
  - Solid Rocket Propulsion
  - Embedded Avionics & Flight Logic
  - Staging & Recovery Systems
  - Flight Simulation (RASAero II, BurnSim, ProPEP)
image: /assets/images/tsCrop.jpg
---

## Project Overview
This project involved the design, fabrication, and flight testing of a **100 mm diameter two-stage solid rocket vehicle** targeting a precise apogee of **18,000 ft AGL**. The system was developed to demonstrate reliable autonomous staging, high structural efficiency, and tightly controlled flight performance using a fully self-designed avionics stack.

The final flight achieved an apogee of **17,718 ft**, validating both the propulsion sizing and staging logic under real flight conditions.

## Vehicle Architecture
The rocket utilized a **self-fabricated composite airframe**, combining fiberglass and carbon fiber to balance stiffness, mass efficiency, and manufacturability. Structural design prioritized axial load paths during boost and clean separation dynamics between stages.

Key features included:
- 100 mm composite airframe with reinforced interstage
- Modular internal bay architecture for avionics and separation systems
- Dual-deployment recovery architecture for safe descent

## Propulsion System
The two-stage propulsion system delivered approximately **8,800 N·s total impulse**, with careful thrust shaping to maintain stability through stage separation.

Motor selection and grain geometry were evaluated using **BurnSim and ProPEP**, while full-stack flight dynamics were modeled in **RASAero II** to verify stability margins, velocity profiles, and apogee targeting.

## Avionics & Staging Logic
All avionics were **self-designed and assembled**, including dedicated modules for:
- Stage separation
- Upper-stage ignition
- Recovery deployment

Staging logic was based on **combined velocity and tilt-angle thresholds**, preventing ignition under unsafe flight attitudes or off-nominal trajectories. This approach significantly red
