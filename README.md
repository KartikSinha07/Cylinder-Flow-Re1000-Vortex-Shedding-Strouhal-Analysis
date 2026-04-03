# 🌊 2D Flow Over Cylinder (Re = 1000)

A 2D CFD simulation of incompressible flow over a circular cylinder using OpenFOAM. This project demonstrates unsteady wake dynamics and vortex shedding behavior at a Reynolds number of 1000, along with frequency analysis of the flow.

---

## 📌 Features

* 🌪️ Simulation of Kármán vortex street behind the cylinder
* ⏱️ Transient flow analysis using pimpleFoam
* 📊 Lift/velocity signal extraction for time-based analysis
* 📈 FFT (Fast Fourier Transform) performed to obtain dominant shedding frequency
* 🔢 Strouhal number calculated from frequency (**St ≈ 0.2333**)
* 🔍 Visualization of velocity and pressure fields in ParaView

---

## 🛠️ Tools Used

* **OpenFOAM** – CFD simulation
* **pimpleFoam** – Transient incompressible solver
* **ParaView** – Post-processing and visualization
* **Python / MATLAB (optional)** – FFT and frequency analysis

---

## 🎯 Purpose

This project was developed to:

* Understand vortex shedding and wake formation behind bluff bodies
* Analyze unsteady flow behavior at moderate Reynolds number
* Extract dominant frequency using FFT
* Compute Strouhal number for validation with standard results
* Build a strong foundation in CFD simulation and post-processing

---


