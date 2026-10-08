# ELARA: Satellite-Based Emissions Monitoring for the Gulf Region

> A satellite-based atmospheric monitoring platform tracking regional emission trends and facility-level air quality across the GCC using Copernicus Sentinel-5P (TROPOMI) data.

---

## Executive Summary
Ground-level air quality monitoring across the Gulf Cooperation Council (GCC) states faces a structural challenge: surface stations are geographically sparse relative to the region’s dense industrial footprint and heavy oil and gas operations.

**Project ELARA** bridges this gap by leveraging high-resolution satellite remote sensing to provide continuous, facility-level emissions records without deploying physical hardware. Using Sentinel-5P (TROPOMI) tropospheric column density measurements, ELARA transforms open-access Earth Observation data into actionable environmental intelligence for regulators, operators, and insurers.

---

## Key Features & Capabilities
* **Facility-Level Attribution:** High spatial resolution ($\approx 3.5 \times 5.5\text{ km}$) isolating industrial plumes from refineries, power plants, and oil ports.
* **Multi-Gas Photochemistry Tracking:** Monitors $\text{NO}_2$, $\text{SO}_2$, $\text{HCHO}$, and particulate proxy trends.
* **Temporal Trend Analysis:** Automated baseline comparisons to quantify percentage shifts across target areas of interest.
* **Lean Deployment Model:** Built using Google Earth Engine with zero upfront hardware costs.

---

##  Quantified Regional Trends (2005–2023)

Consolidated findings from atmospheric studies highlight two distinct pollution regimes over the Arabian Peninsula:

| Region / Location Type | Pollutant | Quantified Trend | Timeframe | Primary Driver |
| :--- | :---: | :---: | :---: | :--- |
| Urban Areas (Middle East-wide) | NO₂ | Up to **+12% / year** | 2005–2014 | Rapid urbanization & rising vehicle ownership. |
| Refineries, Oil Ports, Power Plants | NO₂ | **+2% to +9% / year** | 2005–2014 | Expansion of energy infrastructure. |
| Industrial Hubs (Kuwait City, Dubai) | NO₂ | **+0.1 × 10¹⁵ molec/cm²/yr** | 2005–2023 | Sustained industrial throughput. |
| Qatar, Bahrain, Dammam Corridor | NO₂ | **−1.7% / year** | 2018–2023 | Tightened fuel standards & cleaner power generation. |
| Offshore Platforms (Gulf Comparison) | NO₂ | Up to **+25%** over background | 2004–2022 | Uncontrolled flaring & stationary power generation. |
| Industrial Hotspots (General) | SO₂ | **+0.01 DU / year** | 2005–2023 | High-sulfur fuel oil consumption. |

---

##  Technical Workflow & Implementation
