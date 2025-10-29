# Forward PINN for 2D Acoustic Wave Equation
### _PyTorch Implementation and Hard-Constraint Enforcement_

This repository contains a **PyTorch-based Physics-Informed Neural Network (PINN)** for simulating the **2D acoustic wave equation** with both **soft** and **hard constraint formulations**.  
It reproduces and extends the TensorFlow implementation from **Rasht-Behesht et al. (2022)** in _Journal of Geophysical Research: Solid Earth_.

---

## 🔍 Overview

We solve:
$\frac{\partial^2 \phi}{\partial t^2} = c^2\left(\frac{\partial^2 \phi}{\partial x^2} + \frac{\partial^2 \phi}{\partial z^2}\right), \quad c = 1.$

### Key Features
- Full **PyTorch** reimplementation (original in TensorFlow).
- Soft-constraint formulation for comparison.
- Hard-constraint enforcement of ICs and BCs.

---
