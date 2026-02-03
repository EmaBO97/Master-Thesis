# Master Thesis: Mechatronic Design of Aerial Robots for Agile Maneuvers and Collaborative Transportation

**Author:** Emanuele Bua Odetti  
**Institutions:** École Centrale de Nantes & Università di Genova (EMARO+ Erasmus Mundus)  
**Location:** INRIA Rennes - Rainbow Team  

---

### 📝 Overview
This thesis presents the complete R&D pipeline—from mechatronic design and modeling to experimental validation—of the **BumbleBee platform**, a novel quadrotor optimized for high-performance research. 

### 🚀 Key Technical Contributions:
- **Mechatronic Optimization:** Designed a custom carbon-fiber architecture with a low Center of Mass (CoM) and a Thrust-to-Weight Ratio (TWR) of 4.1, doubling the angular responsiveness compared to previous systems.
- **Advanced Control:** Implemented **Nonlinear Geometric Control on SO(3)** and trajectory generation via **Differential Flatness**. 
- **Software Framework:** Extended the **telekyb3** stack to support axis-asymmetric dynamics, enabling the first successful execution of powerloops and 360° flips within the framework.
- **Sim-to-Real Bridge:** Developed a custom **HIL (Hardware-In-The-Loop) test bench** to identify aerodynamic coefficients ($K_t, K_q$), revealing a 22% discrepancy in manufacturer data and significantly improving simulation fidelity.

### 📁 Contents
- `Thesis_Final_Report.pdf`: The full 80+ page technical report.
- `Project_Poster.svg`: A high-level visual summary of the research and results.
