# Geothermal Reservoir Simulation – CMG STARS

## Overview
This repository contains the base-case geothermal reservoir simulation model
developed using **CMG STARS** with coupled **Thermal–Hydraulic–Mechanical (THM)**
and **geomechanical** modeling.

The model serves as the reference case for subsequent sensitivity analyses.

## Simulator
- CMG STARS
- Version: 2025.20.7035c96e76

## Model Description
- Grid: 34 × 16 × 45 (Cartesian)
- Phases/Components: Single-phase water
- Physics:
  - Thermal flow
  - Rock–fluid heat transfer
  - Geomechanics (3D finite element)
- Aquifer: Semi-analytical infinite-acting aquifer
- Heat loss: Overburden and underburden enabled

## Wells
- Injectors: inj-1, inj-2, inj-3
- Producers: prod-1, prod-2, prod-3
- Injection control: Max STW = 80,000
- Production control: Min BHP = 2000 psi
- Injection temperature: 120 °F

## Base Case
File: stars_geothermal_thm_geomech_base_r001_v01_20250101.dat


This deck is the baseline for all CMOST studies.

## Notes
- Large output files (e.g., `.sr3`, `.out`) are intentionally excluded.
- CMOST cases will be added under the `CMOST/` directory.

## Disclaimer
This model is provided for academic and research purposes only.
