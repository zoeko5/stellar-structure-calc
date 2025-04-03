# ZAMs Stellar Structure Calculation

This project contains a Python implementation of a stellar structure model for a 1.0 M☉ zero-age main sequence (ZAMS) star. The model solves the four coupled equations of stellar structure using the shooting method, and compares the results to MESA.

## Contents

- `stellar_structure_calculation.ipynb` – Full implementation of the model
- `inlist_project` – MESA inlist used to generate a 1.0 M☉ ZAMS star
- `opacities.txt` – Opacities table downloaded from the Opacity Project

To compare against the MESA model, download MESA, copy the star/work folder into a new folder called `mesa_model`, place it in this repo, and replace its `inlist_project` with the one from this repository.
