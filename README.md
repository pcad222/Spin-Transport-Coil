# Spin Transport Coil

Spin transport coils are designed to guide neutron spin **adiabatically** through a magnetic field inside a neutron guide. This is essential for preserving spin polarization in nEDM experiments.

## Motivation
Accurate spin transport ensures that neutrons retain their polarization during transport, critical for experiments involving magnetic resonance or EDM measurements.

## ⚙ Features
- Coil field modeling and visualization
- Adiabatic transport design principles
- Biot–Savart simulation and gradient computation
- Physics-informed optimization (PINNs optional)

##  Physics Background
The transport relies on magnetic field configurations that change slowly in space:
- Satisfies:  
  \[
  \nabla \cdot \vec{B} = 0 \quad \text{and} \quad \vec{B} \cdot \frac{d\vec{S}}{dt} = 0 \text{ (adiabatic condition)}
  \]
- Tools: Biot–Savart law, Maxwell's equations, Runge–Kutta trajectory simulation

## 🗂️ Project Structure
