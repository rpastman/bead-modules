# Using Super-Absorbent Beads to Estimate Contaminant Concentration in Water Samples

Interactive educational modules for high school and undergraduate students on detecting metal contaminants in water with a low-cost, smartphone-based colorimetric bead assay.

**Open the modules:** https://rpastman.github.io/bead-modules/
**Open the Bead App directly:** https://rpastman.github.io/bead-modules/#app

Designed by **Rachael Pastman**, Department of Chemistry, Piedmont University
Faculty advisor: **Dr. Elaine Bailey**

## What's inside

| Module | Topic |
| --- | --- |
| 1 | Environmental contaminants: organic, inorganic, radioactive, and metal, with an interactive periodic table of divalent metals |
| 2 | What's in your water? A guided walkthrough of EWG's Tap Water Database |
| 3 | Detection methods: ICP-MS, ICP-OES, flame AA, GFAA, anodic stripping voltammetry, and XRF |
| 4 | Colorimetric analysis, with a hands-on calibration demo and examples of real color tests |
| 5 | Build your own bead assay: choosing a metal and reagent, a step-by-step procedure, and the Bead App |
| Activity | Choose the Right Tool: match real-world scenarios to the best detection method |

## The Bead App

The Bead App turns smartphone photos of assay beads into a calibration curve and a concentration estimate. For each photo, it finds the 100 most saturated pixels in the bead, takes their median color in CIELAB space, and calculates ΔE against the white backlight. It fits ΔE = a·ln(C + 1) + b to the standards and inverts the curve to estimate unknowns. Curves are saved on the user's device.

## Using it offline

Download `index.html` and open it in any web browser. Everything, including images, is contained in that one file, so it runs without an internet connection.

## References

- Fathalla, M. M. F.; Selvaganapathy, P. R. Colorimetric Detection of Heavy Metal Ions Using Superabsorptive Hydrogels and Evaporative Concentration for Water Quality Monitoring. *ACS ES&T Water* **2022**, *2* (4), 658–666. https://doi.org/10.1021/acsestwater.2c00070
- Screenshots in Module 2 are from EWG's Tap Water Database (https://www.ewg.org/tapwater/) and are used for educational purposes.
- Full citations for each definition, method, and reagent appear within the modules.
