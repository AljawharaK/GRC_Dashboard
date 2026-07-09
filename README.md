# Industrial OT/ICS Risk & GRC Dahboard

Demo: https://aljawharak.github.io/GRC_Dashboard/
An interactive, responsive Governance, Risk, and Compliance (GRC) dashboard purpose-built for operational technology (OT) and industrial control systems (ICS). This platform implements the **ISO/IEC 27005** risk management methodology.

Designed tailored to the engineering and cybersecurity requirements of heavy industries such as energy, oil & gas, and mining.

---

## 🚀 Key Features

* **ISO 27005 Risk Calculation Engine:** Dynamically calculates mathematical inherent and residual risk thresholds using an asset-centric three-variable formula: 
    $$\text{Risk Score} = \text{Asset Criticality (1-5)} \times \text{Threat Likelihood (1-5)} \times \text{Vulnerability Level (1-5)}$$
* **Purdue Model Architecture Mapping:** Categorizes network nodes across operational segments (Level 0: Field Devices up to Level 3: Operations Systems/MES) to track architectural exposure.
* **HSE Integration:** Evaluates threats based on industrial impact, prioritizing Health, Safety, and Environmental (HSE) risks alongside technical risk variables.
* **ICS-Focused Scenario Simulator:** Loaded with pre-configured, realistic manufacturing threats (e.g., unauthorized logic changes on PLCs, unauthenticated SCADA gateway vectors).
* **Live GRC Data Interaction:** Full capabilities to append new custom environment threats directly into the running ledger with dynamic asset KPI card updates.
* **Data Portability:** Features an instant client-side CSV parsing exporter to pull standard asset inventory matrices for external auditing.

---

## 🛠️ Tech Stack & Architecture

* **Frontend UI:** HTML5, CSS3 (Modern Flexbox/Grid alignment with clean typography)
* **Core Execution:** JavaScript (ES6+) managing states, computing matrices, handling structural modals, and rendering tabular datasets on the fly.

---
