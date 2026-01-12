# 🛠️ Assembly & Fabrication Guide

**Project:** Pochita Project
**Status:** 🚧 DRAFT / WORK IN PROGRESS 🚧
**Last Updated:** January 2026

This document outlines the **planned** assembly procedures and design constraints. These strategies are currently being vetted through sketching and CAD modeling before physical fabrication begins.

---

## 🎯 Design Goals
1.  **Soft-Rigid Hybridization:** Successfully integrate a rigid motor chassis into a soft textile body without deformation.
2.  **Serviceability:** Ensure the battery pack and electronics are accessible for maintenance via a zipper interface.
3.  **Haptic Feedback:** The mechanism must provide physical vibration (revving) through the handle when the cord is pulled.

---
## 🧵 Phase 1 Strategy: Soft-Body Modification
*Challenge: Creating internal volume for hardware while maintaining the plush aesthetic.*

**Planned Approach: The "Ventral Access" Method**
* **Incision Strategy:** Instead of cutting raw fabric, the plan is to open the existing bottom seam to prevent fraying.
* **Structural Reinforcement:** Since plush fabric is elastic, **Fusible Interfacing** will be applied to the incision edges. This is critical to create a rigid foundation for the zipper, preventing the fabric from bunching during operation.

---

## ⚡ Phase 2 Strategy: Circuit Logic & Harness
*Challenge: Controlling a high-torque motor with bidirectional input without a microcontroller.*

**Planned Circuit Topology: Hardwired H-Bridge**
* **Bi-Directional Control:** To avoid complex coding for simple movement, a **DPDT (Double Pole Double Throw) Switch** will be wired in a "Crossover" configuration.
    * *Logic:* Switching polarity physically at the hardware level allows the chainsaw to run Forward (Attack Mode) and Reverse (Retract Mode).

---

## ⚙️ Phase 3 Strategy: Mechanical Integration
*Challenge: Transferring torque from a rigid motor to a soft felt belt.*

**Current Design Concepts (Sketch Phase):**
* **Chassis Design:** The internal skeleton is being modeled to clamp the motor securely while providing smooth surfaces that won't tear the fabric skin.
* **Friction Drive:** The pulley system will rely on washer and the limit switch.
* **Trigger Mechanism:** A mechanical limit switch will be mounted in line with a retractable badge reel. The concept is to use the badge reel's spring tension to physically actuate the switch, mimicking a gas engine starter cord.

---

## ⏭️ Next Steps
1.  Finalize "interference fit" tolerances in SolidWorks.
2.  Source correct fabric weight for belt testing.
3.  Begin physical prototyping of the Motor Mount.

