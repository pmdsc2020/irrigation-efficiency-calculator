# Project irrigation efficiency calculator

Browser tool for the stacked product \(E_p = E_c \times E_b \times E_a\). Conveyance, field canal, and application stay separate, so project efficiency is never read off application alone.

Live page: https://pmdsc2020.github.io/irrigation-efficiency-calculator/

## What it calculates

- Conveyance efficiency, \(E_c\): headworks to the block inlet
- Field canal efficiency, \(E_b\): block inlet to the field inlet
- Application efficiency, \(E_a\): field inlet to the root zone
- Project efficiency, \(E_p = E_c \times E_b \times E_a\), in decimals
- Water still in the system from a release at the headworks

Presets reproduce the lined-canal case: \(0.9 \times 0.8 \times 0.55 = 0.40\), and the same canals with \(E_a = 0.80\) give \(0.58\).

Canal chips follow FAO indicative conveyance values for adequately maintained canals. Application bands: surface 0.55–0.80, sprinkler 0.60–0.85, localized 0.85–0.95. Use the local \(E_a\).

Source: FAO Irrigation Manual, Module 1, Chapter 3.2. Day 11 irrigation engineering sketch note.

## Run locally

Open `index.html` in a browser. No build step.
