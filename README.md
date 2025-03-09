# Lab1_assignment

# 🔋 Voltage Source Converter (VSC) Modeling & Control | Renewable Energy Lab

![MATLAB/Simulink](https://img.shields.io/badge/-MATLAB%2FSimulink-0076A8?logo=mathworks&logoColor=white)
![Power Systems](https://img.shields.io/badge/-Power%20Systems-FFD700)
![Lab Report](https://img.shields.io/badge/-Lab%20Report-8A2BE2)

A comprehensive analysis of **Voltage Source Converters (VSCs)** for renewable energy integration, focusing on modeling, control strategies, and grid impedance effects. Developed as part of the Renewable Energy Lab course at *Universitat Politècnica de Catalunya*.

---

## 📌 Overview
This repository contains the first assignment report and simulations for a **Voltage Source Converter (VSC)** system, covering:
- **Average modeling** of VSCs for efficient AC/DC power conversion.
- **Control strategies**: Phase-Locked Loop (PLL), current/power loops, and Park transformations.
- **Grid impedance impact** under varying Short-Circuit Ratios (SCRs).

Key applications include HVDC transmission, renewable energy integration, and grid stability enhancement.

---

## 🚀 Key Features
### 1. **VSC Average Model**
   - Simplified representation of switching devices (IGBTs) for reduced computational complexity.
   - AC grid block with 690V/50Hz parameters and inductor/filter design (30.31 µH).

### 2. **Control Systems**
   - **Phase-Locked Loop (PLL)** for grid synchronization.
   - **Current Control Loop**: Decoupled dq-axis control for active/reactive power regulation.
   - **Power Control Loop**: PI controllers for tracking Pref and Qref.

### 3. **Grid Impedance Analysis**
   - Impact of SCR (1, 3, 5) on active/reactive power tracking.
   - MATLAB simulations demonstrating stability under weak vs. strong grid conditions.

---

## 📊 Simulation Highlights
| **Scenario**               | **Key Insight**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| **SCR = 5** (Strong Grid)  | Fast power tracking with minimal overshoot. Ideal for stable HVDC systems.      |
| **SCR = 3** (Moderate Grid)| Slower response due to higher grid impedance. Requires robust control tuning.   |
| **SCR = 1** (Weak Grid)    | Power tracking fails—risk of voltage collapse. Highlights grid stability limits.|

![Active Power Tracking](https://via.placeholder.com/600x200?text=Active+Power+Response+with+SCR+5+and+SCR+3)  
*Example: Active power response under different SCRs (From Section 3.2-3.7)*

---

## 🛠️ Prerequisites
- **MATLAB/Simulink** for model simulation.
- Basic knowledge of power electronics and dq-axis control theory.

---


---

## 📜 References
- Supervised by **Prof. Marc Cheah Mañé** (UPC).
- Includes Park transformation, PI controller tuning, and grid impedance modeling.

---

## 🌟 Acknowledgments
Special thanks to the **Department of Electrical Engineering, UPC**, for providing resources and guidance in renewable energy systems.

---

🔗 **Explore the [Full Report](VSC_ASSIGNMENT1_REPORT.pdf) for detailed analysis!**
## 📂 Repository Structure
