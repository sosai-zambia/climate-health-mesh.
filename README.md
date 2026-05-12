# Climate-Health Mesh: Open-Source Energy-Health Resilience Data Module

**Sosai Renewable Energies Company Limited — Zambia**
**Repository Status:** In active development | First release targeted Q3 2026

---

## Overview

This repository contains the open-source data module developed by Sosai Zambia that correlates real-time solar mesh-grid energy performance data with community-level child health service delivery indicators. It is designed to run on top of the MeshNova Skyline cloud platform's REST API and is intended to be freely adaptable by energy developers, health ministries, and community health programmes across sub-Saharan Africa.

The module generates **Climate-Health Resilience Scores** for rural communities — identifying when and where energy system degradation is placing children's health services at risk, and enabling anticipatory preparedness responses before climate shocks translate into disrupted care.

---

## The Problem

In rural Zambia, only 4% of communities have access to on-grid electricity. In Chitambo District, Central Province — one of the most remote districts in the country — health posts lack reliable power for vaccine cold chains, night delivery lighting, and water pump operation. Climate shocks including floods and droughts further disrupt already fragile health infrastructure. Children under five and pregnant women carry the greatest burden of this vulnerability.

The critical gap is not just the absence of energy — it is the absence of **data linking energy availability to health service continuity**, which means decision-makers cannot see the problem coming or respond in a coordinated way when it arrives.

---

## What This Module Does

The Climate-Health Mesh module connects two data streams that have never been systematically integrated at community level in rural Zambia:

1. **Energy performance data** — real-time grid uptime, battery state of charge, per-node consumption, and anomaly alerts from MeshNova Skyline's REST API across deployed mesh-grid clusters.

2. **Health service delivery indicators** — vaccine cold chain continuity hours, water pump operation hours, health post lighting availability, and community health worker connectivity status, collected via lightweight structured inputs from local health workers.

The module applies machine learning analytics to correlate these streams, producing:

- **Community Climate-Health Resilience Scores** updated in near real-time
- **Predictive vulnerability flags** when grid degradation patterns suggest imminent health service disruption
- **Preparedness alerts** pushed to local government and community health workers in accessible formats requiring no technical expertise
- **Aggregated open datasets** exportable for use by health ministries, REA, and UNICEF country offices

---

## Target Communities

Initial pilot deployment: **Chitambo District, Central Province, Zambia**

Chitambo District is among Zambia's most remote and underserved areas. Chitambo Hospital serves tens of thousands of people across the district, with surrounding communities entirely off-grid. The district's geographic isolation, climate exposure, and traditional community structures make it a representative and high-impact pilot site for this methodology.

---

## Technology Stack

| Layer | Technology |
|---|---|
| Energy hardware | MeshNova Mesh-Grid (NodeFlex/NodeNet Hubs, Branch endpoints) |
| Cloud operations | MeshNova Skyline Platform |
| Data integration | Skyline REST API + Webhooks |
| ML analytics | Python (scikit-learn); anomaly detection and demand forecasting |
| Health data inputs | Lightweight mobile-compatible structured forms (ODK-compatible) |
| Output dashboards | Open-source visualisation (to be confirmed during development) |
| License | Apache 2.0 (planned) |

---

## Organisational Background

**Sosai Renewable Energies Company Limited (Zambia)** was incorporated on 29 July 2024 (PACRA Registration No. 120241010506) as a private company engaged in electric power generation, transmission and distribution.

It is the Zambian subsidiary of **Sosai Renewable Energies (Nigeria)**, founded in 2010, which has delivered energy access to over 45,000 families and more than 2 million Nigerians across 15 years of operations. Sosai Nigeria is a named RESCO partner in the REA-Okra Solar DARES mesh-grid programme, currently deploying mesh-grid technology to underserved Nigerian communities — the operational methodology that directly informs this Zambia deployment.

Sosai is a women-led organisation with a 60% women C-suite and a strong track record of integrating productive use of energy — solar water pumps, cold storage, agro-processing — alongside household electrification to build community economic resilience.

---

## Development Roadmap

| Milestone | Target |
|---|---|
| Repository established and architecture documented | May 2026 |
| MeshNova technology partnership formalised | Q2 2026 |
| Chitambo site surveys and health facility mapping completed | Q3 2026 |
| Alpha version of data module developed and tested | Q3 2026 |
| Pilot deployment — first mesh-grid cluster, Chitambo | Q3 2026 |
| Health worker data input system tested in field | Q4 2026 |
| First Climate-Health Resilience Scores generated | Q4 2026 |
| Open dataset published | Q1 2027 |
| Full open-source release under Apache 2.0 | Q1 2027 |

---

## Contributing

This project is being developed as an open-source public good. Contributions, peer review of the data architecture, and adaptation for other country contexts are welcome. Please open an issue to start a conversation.

---

## Contact

**Sosai Renewable Energies Company Limited**
17 Northmead, Lusaka, Lusaka Province, Zambia
[sosai@sosairen.org](mailto:sosai@sosairen.org)
[www.sosairen.org](http://www.sosairen.org)

---

*This repository is being developed with support from the UNICEF Venture Fund Climate Ventures application process. Sosai Zambia is committed to open-source licensing of all funded outputs by month six of any investment period.*
