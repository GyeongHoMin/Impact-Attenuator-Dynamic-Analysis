# Impact Attenuator Dynamic Analysis — SV  Electric Vehicle

## Overview
Dynamic (explicit) FE analysis of the impact attenuator (crash energy absorber) designed for the SV Formula Student electric vehicle's front frame assembly. The analysis evaluates whether the attenuator meets the energy absorption and deceleration requirements specified by Formula Student structural rules.

- **CAD Model:** Frame assembly with impact attenuator, modeled in CAD and exported as STEP
- **Solver:** RADIOSS (Altair HyperWorks)
- **Analysis Type:** Explicit dynamic impact simulation
- **Attenuator Thickness:** 2 mm

## Key Results

| Metric | Value |
|---|---|
| Peak Deceleration | 36.2 g |
| Average Deceleration | 12.8 g |
| Energy Absorbed | 7,550 J |

The deceleration-time history was extracted from the RADIOSS result file (.h3d) and post-processed in Excel to compute the average deceleration over the impact event.

## Files
- `Result.h3d` — RADIOSS/HyperView simulation result file
- `충격흡수장치.step` — Impact attenuator + frame assembly CAD model
- `평균감속.xlsx` — Time-history deceleration data and average deceleration calculation
- `정리_파일.docx` — Summary of key analysis results

## Notes
This analysis was conducted as part of the SV Formula Car Research Club's structural analysis activities, supporting impact attenuator design verification for the team's electric formula vehicle.
