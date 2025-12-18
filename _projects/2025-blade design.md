---
layout: project
title: Small Wind Turbine Blade Design
description: Experimental design and testing of a small-scale wind turbine blade.
technologies: 
  - Fusion 360
  - MATLAB
  - Wind Tunnel Testing
  - Aerodynamic Modeling
  - Experimental Data Analysis

image: /assets/images/turbineCov2.png
---

## Project Overview

As part of MAE 4272 (Fluids and Heat Transfer Laboratory), our team designed, fabricated, and experimentally tested a three-blade small wind turbine rotor for operation in Cornell’s Big Blue low-speed wind tunnel. The objective was to maximize power extraction under low-Reynolds-number conditions while satisfying strict geometric, structural, and testing constraints. Our goal was to use wind-resource statistics to target the operating conditions that contribute most to long-term energy production.

## Design Process

We began by analyzing a Weibull wind-speed distribution (k = 5, c = 5 m/s) and identified that wind speeds near 5.3 m/s dominate long-term energy availability due to the cubic dependence of power on velocity. This informed a fixed design operating point at 1900 rpm, corresponding to a tip-speed ratio of approximately 6.7, a high-efficiency range for three-bladed rotors.

For the blade geometry, we selected the NACA 4412 airfoil for its reliable performance and predictable stall behavior in the Reynolds-number range of approximately 30,000–60,000. A square-root chord taper concentrated aerodynamic area near the hub where tangential velocity is low, while a spanwise twist distribution was implemented to maintain favorable angles of attack across the blade at the design operating point. Structural checks verified safe operation against both root bending stresses and the magnetic particle brake torque limit.

![Blade twist and taper geometry]({{ "assets/images/twist&taper.png" | relative_url }})
*CAD views showing the prescribed spanwise twist and square-root chord taper used to maintain efficient angles of attack along the blade.*


## Testing & Results

The rotor was tested by generating power curves across multiple tunnel velocities (approximately 3.4–6.5 m/s). At each speed, brake torque was incrementally increased and equilibrium torque–RPM data were recorded to compute power. The measured curves exhibited the expected aerodynamic behavior, with power peaking at intermediate rotational speeds.

![Measured power curves across tunnel velocities]({{ "assets/images/power_curve.png" | relative_url }})
*Measured power curves across multiple tunnel velocities, with the design operating point highlighted near 1900 rpm.*

Across all test cases, maximum power consistently occurred near 1900 rpm and within the 5.3–6.0 m/s wind-speed range, closely matching predictions from the statistical wind analysis and blade design. While geometric constraints limited maximum chord length and reduced absolute power, the rotor achieved its primary objective: concentrating performance where long-term energy contribution is highest.


### Probability-Weighted Performance at Design Operating Point

The table below summarizes measured power output near the design operating speed (≈1900 rpm) and its relative contribution to long-term energy production, based on a Weibull wind-speed distribution.

| Wind Speed (m/s) | Power @ 1900 rpm (W) | Relative Occurrence | Weighted Contribution |
|------------------|---------------------:|--------------------:|----------------------:|
| 4.0              | 0.38                 | Low                 | 0.10                  |
| 5.0              | 1.15                 | High                | **0.42**              |
| 5.5              | 1.70                 | High                | **0.59**              |
| 6.0              | 1.85                 | Moderate            | **0.49**              |

**Key takeaway:** Wind speeds near 5–6 m/s dominate long-term energy contribution, validating the selected design operating point.

### Efficiency Relative to Theoretical Maximum

At the design wind speed (≈5.3 m/s), the rotor produced a peak power of approximately 1.8 W, corresponding to a power coefficient of \( C_P \approx 0.20 \), or about 34% of the Betz limit. This efficiency is reasonable for a small, low-Reynolds-number rotor and occurred in the same wind-speed range identified by the Weibull-based energy analysis, validating the design strategy.


## My Contribution

I led the design analysis and performance interpretation, including Weibull wind-resource modeling, operating-point selection, and blade-geometry rationale (airfoil choice, chord taper, and twist). I also contributed to structural safety calculations, participated in wind-tunnel testing, and analyzed power-curve data to validate the design hypothesis. I synthesized the results into the final report and presentation, emphasizing the connection between statistical modeling, aerodynamic design, and experimental outcomes.


