# Solar Radiation Pressure Sensitivity Study (LEO)

## Overview

This project investigates the long-term effects of Solar Radiation Pressure (SRP) on lightweight satellites in Low Earth Orbit (500 km altitude).

While SRP is significantly smaller than gravitational force, its continuous application can cause measurable orbital drift, particularly for satellites with high area-to-mass ratios.

## What This Project Includes

- 2D orbital propagation using Newton’s law of gravitation
- Solar radiation pressure force modeling
- Earth eclipse shadow modeling (SRP disabled in shadow)
- Attitude-dependent projected area using spin stabilization
- 7-day mission-level drift sensitivity trade study
- Critical area-to-mass threshold identification

## Engineering Question

At what area-to-mass ratio does SRP become mission-relevant for a 7-day LEO mission?

## Key Insight

Solar radiation pressure becomes increasingly significant as area-to-mass ratio increases. Spin stabilization reduces drift by averaging projected area over time.

## Skills Demonstrated

- Orbital mechanics fundamentals
- Space environment modeling
- Numerical integration (scipy solve_ivp)
- Parametric trade studies
- Engineering threshold analysis
- Systems-level interpretation
