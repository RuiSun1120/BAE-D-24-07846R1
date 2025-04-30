# CFD Simulation Data for Outdoor Transmission Study

This repository provides the mesh, field data, and post-processing results related to the manuscript titled:

**"[Manuscript Title]"**

## 📌 Purpose

To improve transparency and reproducibility, this repository includes:
- Mesh files used in the grid independence study
- Velocity field data at pedestrian height
- Particle tracking results
- Mesh quality indices
- Simulation logs with convergence and runtime info
- Re-generated figures from raw simulation output

All figures have been recreated using original CFD results (no image-based extraction), and raw data is directly accessible here.

---

## 📁 Directory Overview

- `mesh/`: Coarse, medium, and fine mesh structures.
- `windField/`: Sampled velocity field data at selected time points or locations.
- `particleTracks/`: Particle distributions for three test cases, updated and verified.
- `postProcessing/figures/`: All contour and visualization figures re-generated from raw data.
- `meshQuality/`: Mesh quality metrics (skewness, orthogonality, aspect ratio).
- `simulationLogs/`: Residual histories and CPU usage logs.
- `supplementaryLink.txt`: If file sizes exceed GitHub limits, links to full datasets hosted externally (e.g., Google Drive).

---

## 📝 Notes

- The airflow field was solved as a **steady-state RANS** problem.
- Particle transport was modeled as a **transient Lagrangian** process based on the converged flow field.
- Updated particle data in `case3/` corrects an earlier error where a testing case (with different inlet velocity) was mistakenly used in the previous version.

---

## 🔗 Contact

For any questions or clarification, please contact:  
**[Your Name]**  
**[Institution]**  
**[Email]**
