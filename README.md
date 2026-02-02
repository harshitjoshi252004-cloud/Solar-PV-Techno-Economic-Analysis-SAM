# 6.5 MW Utility-Scale Solar PV Analysis

## 📄 Project Overview
This repository hosts a techno-economic feasibility study for a **6.5 MW DC** utility-scale photovoltaic system located at **Latitude 27.45, Longitude 71.95**.

The project was simulated using the **NREL System Advisor Model (SAM)** to analyze energy yield, system losses, and financial returns over a 25-year lifespan. The design utilizes bifacial modules and single-axis tracking to optimize performance in a high-irradiance environment.

---

## 🛠 Technical Specifications
The system is engineered for utility-scale application with the following configuration:

* **System Capacity:** 6.54 MW DC / 5.01 MW AC
* **DC/AC Ratio:** 1.30
* **Module Type:** Aptos Solar Technology (DNA-144-BF10-530W) - Mono-c-Si Bifacial
* **Module Quantity:** 12,320 units
* **Inverters:** Sungrow Power Supply (SC2500U) - 2 units
* **Tracking System:** Single-axis tracking (0.3 GCR, Backtracking disabled)
* **Azimuth:** 180° (South)

---

## 📊 Performance Metrics (Year 1)
The simulation results indicate high efficiency due to the use of bifacial technology and tracking.

| Metric | Value |
| :--- | :--- |
| **Annual Energy Production** | 13,379,929 kWh (13.38 GWh) |
| **Capacity Factor** | 23.4% |
| **Performance Ratio** | 0.81 |
| **Nominal POA Irradiance** | 80,653,160 kWh |

---

## 💰 Financial Analysis
The project is modeled under a **Single Owner** financial structure.

* **Total Installed Cost:** $3,509,218 ($0.54/Watt)
* **PPA Price (Bid):** 5.5 cents/kWh
* **LCOE (Nominal):** 4.9 cents/kWh
* **Net Present Value (NPV):** $1,344,800
* **Internal Rate of Return (IRR):** 22.2% (at Year 20)
* **Inflation Rate:** 2.5%
* **Real Discount Rate:** 6.4%

---

## 📉 System Losses
A detailed loss tree analysis was conducted to identify efficiency reductions:

* **Module Deviation from STC:** -12.27%
* **Soiling:** -3.0%
* **Inverter Efficiency:** -2.4%
* **DC Wiring:** -1.5%
* **Reflection (IAM):** -1.12%
* **Diodes and Connections:** -0.5%

---

## 📂 Repository Contents
* `Solar_Analysis_Model.sam` - The source simulation file (NREL SAM).
* `Detailed_Report.pdf` - Comprehensive PDF report including monthly output graphs and cash flow tables.
* `README.md` - Project documentation and summary.

## 🚀 Tools Used
* **System Advisor Model (SAM) 2025.4.16:** Used for performance modeling and financial analysis.
