![Gemini VTOL Preview](preview.png)

## 🛸 Project Overview
The Gemini VTOL is an experimental single-seat personal flight vehicle utilizing a ducted, contra-rotating dual-propeller system. 
It is currently in the digital prototyping and simulation phase, utilizing WebGL and advanced flight dynamics engines to test weight-shift kinematics and thrust vectoring.

## ⚙️ Technical Highlights

* **Propulsion:** Triple turboshaft configuration
* **Lift System:** Contra-rotating 2-prop array
* **Airframe:** Lightweight with a triangulated suspension footprint.
* **Ducting:**  Carbon Fiber aerodynamic duct
* **Flight Controls:** Articulated weight-shift pendulum. cyclic dynamics, collective and thrust-vectored yaw authority.
* **Avionics:** Integrated HUD.

## 📁 Repository Structure
* `gemini_150.glb`: The 3D geometry and kinematic hierarchy for simulation testing.
* `aircraft.json`: Physics configuration dictating mass distribution, IK control linkages, and thrust parameters.

## 🛠️ Simulation Setup (GeoFS)
To fly this craft in GeoFS:
1. Ensure "Mix Roll/Yaw" is **disabled** in your simulator settings to prevent uncommanded flat spins.
2. It is highly recommended to use **Mouse Control** for the Cyclic (Pitch/Roll) and keyboard inputs for Collective/Yaw.


---
*Designed and engineered by Howard.*
