# hp-quadcopter 

Ground up engineering project designing and building a high peformance quadcopter. Every component of airframe is designed from scratch in Fusion360 and fabricated in a p2s 3d printer, final iteration will be a carbon fiber filled pla filament. The project is structured in two iterations - this repository documents Iteration 1 (6S) which establishes a peformance baseline. Targeting 160-175 km/h, with Iteration 2 (8S) targeting 200+ km/h.

## Project Goals 
-Design a custom airframe rocket-geometry in Fusion360
-Run CFD analysis on the fuselage geometry using SimScale to quantify drag reduction vs a standard plate center stack
-Engineer and document component selections with rationale
-Achieve a GPS measured top speed exceeding 140 km/h on 6S 
-Document full process to professional standard.

## Specs - Iteration 1 
-Frame: Custom Design, carbon fiber filled filament 
-Motors: AOS Supernova 2207 1980 KV x4
-Power System: 6S LiPo, 1000-1300mAh
-Flight Controller: SpeedyBee F7 V3
-Target Speed: 160-175 km/h calm air 

## Tools Used
-**Fusion 360**: Airframe CAD Design
-**SimScale**: CFD analysis for drag reduction
-**MATLAB**: Flight data analysis and plotting
-**Bambu Lab P2S**: Fabrication 

## Repository Structure
- '/docs' - Document requirements, test procedures, test reports
- '/cad' - Fusion 360 design files
- '/analysis' - Flight data analysis scripts
- '/aero' - SimScale results, tests

## Project Status 
Phase 1 - Requirements complete, beginning frame design 
