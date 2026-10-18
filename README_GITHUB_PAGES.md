# Publish the thermal-insulation calculator with GitHub Pages

This folder contains a ready-to-publish static site:

- `index.html` — the interactive calculator
- `Insulation_Input_Template.xlsx` — the blank import template

The calculator reads completed input files locally in the browser. It does not send input data to the site host. The relative template download link is already configured, so keep both files in the repository root.

## Publish steps

1. Create a GitHub repository (public if the site should be public).
2. Upload `index.html` and `Insulation_Input_Template.xlsx` to the repository root and commit them to the `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for the Pages deployment to finish. GitHub will show the site URL in the Pages settings; open it and test both the calculator and the template download.

The report's ISO 12241:2022 reference is informational; the calculator does not claim verified conformity to the full standard.
