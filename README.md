# Sector Rate Sensitivity

## Project Fuction & Motivation
This project analyzes how different equity sectors respond to changes in U.S. interest rates, with the goal of identifying relative sensitivity and defensive characteristics across industries.

## Research Questions
- How sensitive are sector-level equity returns to changes in U.S. interest rates?
- Do different sectors exhibit heterogeneous responses to interest rate movements?

## Data Sources
- Sector-level equity returns (sector ETFs) from public market data sources.
- U.S. 10-year Treasury yield data from public economic data sources.

## Methodology
- Construct time-series returns for sector-level equities.
- Estimate sector-specific interest rate exposure using regression-based models.
- Compare sensitivity estimates across sectors via cross-sectional analysis.

## Key Results
- Interest rate sensitivity varies meaningfully across equity sectors
- Some sectors demonstrate more defensive behaviors during rising-rate periods.
- Results highlight heterogeneity in sector exposure to interest-rate risk.

## Visualizations
The figure below summarizes estimated sector sensitivity to intereest rate changes.

## How to Reproduce
Install dependencies:
```bash
   pip install -r requirements.txt
