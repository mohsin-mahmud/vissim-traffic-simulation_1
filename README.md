# 🚦 Microscopic Traffic Simulation in PTV Vissim: Mixed-Traffic Arterial & School-Zone Congestion

[![PTV Vissim](https://img.shields.io/badge/PTV%20Vissim-3D%20Microsimulation-blue.svg?style=for-the-badge&logo=compass)](https://www.ptvgroup.com/)
[![Traffic Engineering](https://img.shields.io/badge/Domain-Traffic%20Engineering-green.svg?style=for-the-badge)](https://en.wikipedia.org/wiki/Traffic_engineering_(transportation))

> **Hands-on simulation project:** Recreating real-world mixed-traffic dynamics and exploring how low-cost operational interventions can unclog urban bottlenecks during peak school-pickup hours.

---

## 🎥 Simulation Preview

<video src="https://github.com/mohsin-mahmud/vissim-traffic-simulation_1/raw/refs/heads/main/Vissim_Simulation.mp4" controls="controls" width="100%"></video>

*3D Microscopic view showing non-lane-based heterogeneous traffic, curbside school-pickup queues, median dividers, and corridor progression modeled in PTV Vissim.*

---

## 📌 Project Overview & Objective

Urban corridors in developing cities face unique friction during morning drop-offs and afternoon school-pickup hours:
- A chaotic blend of **passenger cars, CNG auto-rickshaws, motorbikes, and non-motorized cycle rickshaws** sharing the same road without rigid lane discipline.
- **Double-parking and roadside loading** that often cuts arterial capacity in half.
- Unregulated pedestrian crossings adding stop-and-go turbulence.

This simulation models a **480-meter dual-carriageway arterial corridor** (inspired by the busy **SUST–Ambarkhana Corridor** in Sylhet, Bangladesh) to understand how traffic flows under pressure—and to visually test smarter geometric and operational solutions.

---

## 🛠️ What I Built & Modeled

- 🚗 **Heterogeneous / Mixed-Traffic Fleet:** Calibrated non-lane-based driving behavior (Wiedemann car-following, lateral clearances, and bilateral overtaking) across 5 vehicle classes:
  - Private Cars & Microbuses
  - Three-Wheeled Auto-Rickshaws (CNGs)
  - Motorized Two-Wheelers
  - Non-Motorized Cycle Rickshaws
  - Transit Buses
- 🛣️ **Geometric Corridor Realism:** Modeled 3-lane carriageways, median islands with physical vegetation barriers, U-turn openings, and connecting side roads.
- 🅿️ **Pick-Up Bay Dynamics:** Implemented parking routing decisions (PRDs) and dynamic dwell times to replicate parents waiting, parking, and unparking.
- 🚧 **Bottleneck Interventions Tested:**
  - Dedicated **single-row curbside loading bays**
  - **Yellow cross-hatched anti-double-parking demarcations**
  - **Diverted overflow staging areas** on adjoining side roads
  - Pedestrian crossing batching and conflict resolution

---

## 🧰 Tech Stack & Tools

| Component | Tool / Methodology |
| :--- | :--- |
| **Traffic Microsimulation** | **PTV Vissim** (Car-following, lateral behavior, conflict areas, PRDs) |
| **3D Modeling & Environment** | **PTV Vissim 3D Engine** (Custom textures & median demarcations) |
| **Methodology** | Translating field observations into link-connector networks, iterative debugging of lateral clearances, and visual storytelling for urban planners. |

---

## 🚀 What's Next / Work in Progress

- [ ] Further tuning lateral gap-acceptance for non-lane-based three-wheelers.
- [ ] Exporting trajectory files (FZP) for detailed surrogate safety assessment (TTC / PET).
- [ ] Extracting operational MOEs (delay, speed, and LOS) for comparative analysis.

---

### 🤝 Connect & Feedback
If you are passionate about **traffic modeling, smart mobility, or urban transportation engineering**, I'd love to connect and hear your thoughts. 

⭐ *If you enjoyed this simulation preview, feel free to give this repository a star!*
