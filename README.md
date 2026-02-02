# 6.5 MW Utility-Scale Solar PV Analysis ☀️

## Project Overview
[cite_start]This repository contains a techno-economic feasibility study for a **6.5 MW DC** utility-scale photovoltaic system[cite: 1]. [cite_start]The project was modeled using the **System Advisor Model (SAM)** to simulate energy production, system losses, and financial viability over a 25-year project lifespan[cite: 7].

[cite_start]The system is designed with bifacial modules and single-axis tracking to maximize specific yield in a high-irradiance location (Lat 27.45, Lon 71.95)[cite: 1, 11].

## 🛠 Technical Specifications
The system design focuses on high-efficiency components and tracking technology to optimize the Capacity Factor.

* [cite_start]**Total Capacity:** 6.54 MW DC / 5.01 MW AC [cite: 2, 8]
* [cite_start]**DC/AC Ratio:** 1.30 [cite: 8]
* [cite_start]**Modules:** 12,320 units of Aptos Solar Technology (DNA-144-BF10-530W) [cite: 2]
    * [cite_start]*Type:* Mono-c-Si Bifacial [cite: 2]
* [cite_start]**Inverters:** 2 units of Sungrow Power Supply (SC2500U) [cite: 8]
* [cite_start]**Tracking:** 1-axis tracking with 0.3 GCR (Ground Coverage Ratio) [cite: 11]

## 📊 Performance Analysis
[cite_start]The simulation accounts for detailed system losses, including soiling (-3%), DC wiring (-1.5%), and bifacial electrical mismatch[cite: 49, 73, 59].

* [cite_start]**Annual Energy Production (Year 1):** 13,379,929 kWh (13.38 GWh) [cite: 15]
* [cite_start]**Capacity Factor:** 23.4% [cite: 15]
* [cite_start]**Performance Ratio:** 0.81 [cite: 15]
* [cite_start]**Nominal POA Irradiance:** 80,653,160 kWh [cite: 46]

## 💰 Financial Highlights
[cite_start]The project is modeled under a Single Owner financial structure with a 20-year internal rate of return target[cite: 1, 13].

* [cite_start]**Total Installed Cost:** $3,509,218 ($0.54/Watt) [cite: 5]
* [cite_start]**PPA Price (Bid):** 5.5 cents/kWh [cite: 9]
* [cite_start]**Levelized Cost of Energy (LCOE):** 4.9 cents/kWh [cite: 13]
* [cite_start]**Net Present Value (NPV):** $1,344,800 [cite: 13]
* [cite_start]**Project IRR (Year 20):** 22.2% [cite: 13]

## 📉 Loss Diagram Summary
A detailed loss tree analysis was performed to identify efficiency drops:
1.  [cite_start]**Soiling:** 3% loss [cite: 49]
2.  [cite_start]**Module Deviation from STC:** 12.27% loss [cite: 65]
3.  [cite_start]**Inverter Efficiency:** 2.4% loss [cite: 90]
4.  [cite_start]**DC Wiring:** 1.5% loss [cite: 73]

## 📂 Repository Structure
* `Solar_Project.sam` - The source file for the NREL System Advisor Model.
* `Report.pdf` - Full PDF report containing loss diagrams and cash flow tables.
* `README.md` - Project documentation.

## 🚀 Tools Used
* [cite_start]**NREL SAM (System Advisor Model):** For performance and financial modeling[cite: 3].
