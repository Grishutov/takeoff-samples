# Takeoff samples

Samples of my quantity takeoff and drafting work. All drawings are public or fictitious. No client information.

| Sample | Type | Files |
| --- | --- | --- |
| [1. Structural steel takeoff, portal-frame shed](#1-structural-steel-takeoff---portal-frame-shed) | Steel member list, weights, markup | `steel-shed/` |
| [2. Painting takeoff, residence bedroom wing](#2-painting-takeoff---residence-bedroom-wing) | Finishes takeoff, markup | `Painting_Takeoff_*` |
| [3. US residential permit sheet](#3-us-residential-permit-sheet) | AutoCAD drafting | `SMP-1_*.pdf` |

## 1. Structural steel takeoff - portal-frame shed
A fictitious 24 x 12 m machinery shed (A3 framing sheet) measured the way steel fabricators ask for it: steel members only, plates, bolts and nuts excluded.

- `steel-shed/S1_Machinery_Shed_Framing.pdf`: the drawing
- `steel-shed/S1_Machinery_Shed_Takeoff_Markup.pdf`: every member colour-coded by type, count tags, legend with totals
- `steel-shed/Steel_BoM_Machinery_Shed.xlsx`: bill of materials by mark (qty, length, kg/m, kg), subtotals, 5 % allowance, summary by section, notes and exclusions

![Steel takeoff markup](images/S1_steel_markup.png)
![Steel BoM](images/S1_steel_bom.png)

Built with my [steel-takeoff-tools](https://github.com/Grishutov/steel-takeoff-tools).

## 2. Painting takeoff - residence, bedroom wing
Source drawing: the public example floor plan from the New Zealand MBIE "Guide to applying for a building consent" (2007).

- `Painting_Takeoff_Bedroom_Wing.xlsx`: room-by-room takeoff of walls, ceilings, doors, trims and openings. Every line is referenced to the drawing; assumptions, items not painted and clarifications are on separate sheets.
- `Painting_Takeoff_Markup.pdf`: colour-coded markup of what was measured.

Measured to NZ painting practice: m² and lm, openings over 0.5 m² deducted. The public set has no sections, so wall heights are assumptions and are flagged in yellow.

![Painting takeoff markup](images/P1_markup.png)

## 3. US residential permit sheet
- `SMP-1_Kitchen_Riser_Panel_Schedule.pdf`: 11x17 sheet plotted from AutoCAD with kitchen DWV and water supply riser isometrics, electrical riser, 24-space panel schedule and NEC 220.83(A) service load calculation. Fictitious project data, not for construction.

![Permit sheet sample](images/F1_sheet.png)
