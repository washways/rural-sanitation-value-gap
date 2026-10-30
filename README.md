# Rural Sanitation Value Gap

A static GitHub Pages advocacy tool comparing recorded sanitation finance with the investment needed to close rural basic-sanitation gaps in Least Developed Countries, while making clear that mortality is only one part of sanitation's value.

## v9 changes

- Adds a prominent **whole sanitation benefit case** to the country page.
- Shows six major benefit channels:
  - under-five mortality
  - illness and health costs
  - caregiving and productivity
  - nutrition and development
  - dignity, privacy and safety
  - education and daily life
- Only under-five diarrhoeal mortality is marked as monetised in the VSL calculation.
- Shows the modelled mortality-only return beside WHO's broader sanitation benchmark of about US$5.50 returned per US$1 invested.
- Adds Malawi context from UNICEF Malawi: poor sanitation and hygiene have been cited as costing about US$57 million per year, or 1.1% of GDP, through health costs and productivity losses.
- Removes mortality-return rankings from the main LDC comparison and replaces them with rural sanitation-gap rankings.
- Renames the VSL tab **Mortality value (VSL)** to make its narrow scope explicit.
- Keeps financing need and the wider benefit case conceptually separate.
- Retains low / central / high sanitation cost scenarios, public-versus-household financing scenarios, continuous LMIC VSL transfer, phased investment and benefit timing, and CSV export.

## Interpretation

The headline financing comparison is not a valuation of a child.

The VSL section monetises only modelled under-five diarrhoeal mortality. It is deliberately partial and should not be presented as the total sanitation return.

Broader benefits include morbidity reduction, lower household and health-system costs, fewer caregiving and sick days, productivity, nutrition and development, education, dignity, privacy, safety, convenience, environmental benefits and resilience.

WHO continues to cite a global economic analysis estimating about US$5.50 in benefits for every US$1 invested in sanitation through lower health costs, increased productivity and fewer premature deaths. This is shown as external context, not multiplied into country results.

## Main sources

- World Bank Indicators API
- OECD Creditor Reporting System
- WHO sanitation fact sheet
- UNICEF sanitation
- UNICEF Malawi WASH
- UNICEF / Hutton & Varughese sanitation costing
- Cochrane sanitation intervention review
- 2025 LMIC VSL value-transfer study

## Related tools

- WASHCost Malawi: https://apps.washways.org/WASHCostMalawi/
- Child WASH Health Impacts: https://apps.washways.org/ChildWASHHealthImpacts/
- Sanitation Impact Modeler: https://washways.org/sanitation-model/
- Sanitation Equity & Performance: https://washways.org/sanitation-equity-performance/
- OECD Expenditure Explorer: https://apps.washways.org/OECD-Expenditure-Explorer

## Deploy on GitHub Pages

1. Upload `index.html`, `README.md`, `.nojekyll` and `DEPLOY.txt` to the repository root.
2. Open **Settings > Pages**.
3. Select **Deploy from a branch**.
4. Select `main` and `/(root)`.
5. Save.

No build process is required. The favicon is embedded in `index.html`.
