# building-energy-advisor

**Live tool:** [moezusb.github.io/building-energy-advisor](https://moezusb.github.io/building-energy-advisor/)

A browser-based screening tool that takes a building profile - province, type, floor area, heating fuel, and energy spend - and returns ranked decarbonization recommendations with estimated annual savings, payback periods, and carbon reduction.

## What it does

- Analyzes 7 retrofit interventions (heat pumps, envelope upgrades, solar, controls, and more) against your building profile
- Ranks recommendations by your chosen priority: maximize savings, minimize carbon, or shortest payback
- Surfaces the top option with plain-language rationale tailored to your province and fuel type
- Lets you compare any two options side-by-side
- Includes an expandable calculation breakdown showing the exact inputs and rates behind every estimate
- Reference guide at the bottom covers all interventions — costs, savings ranges, implementation steps, and available Canadian incentives

## Data sources

Estimates are based on publicly available Canadian federal datasets. This is a screening tool, not a replacement for a certified energy audit.

| Source | Used for |
|---|---|
| Natural Resources Canada (NRCan) | Building energy intensity benchmarks, retrofit cost ranges |
| Environment & Climate Change Canada (ECCC) | Fuel emission factors, federal carbon price |
| Canada Energy Regulator (CER) | Provincial grid emission intensity (kg CO₂/kWh) |
| CMHC / Canada Greener Homes | Incentive values, retrofit cost guidance |
| NRCan RETScreen | Savings multiplier benchmarks by intervention and fuel type |
| Provincial utility tariff schedules | Electricity and gas rates (Q1 2026) |

