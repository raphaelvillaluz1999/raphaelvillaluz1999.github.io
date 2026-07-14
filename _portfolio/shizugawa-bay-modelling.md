---
title: "Shizugawa Bay Biogeochemical Modelling"
excerpt: "Developed an add-on module to analyse the effects of Shizugawa Bay oysters on bay water quality."
collection: portfolio
---

# Scientific Challenge
Shizugawa Bay is a significant source of seafood for Japan's market. Recent data indicates observed hypoxia 
around oyster raft areas developing during summer. A coupled biogeochemical model aimed at 
diagnosing factors that contribute to the degredation of the bay's water quality has been in development, 
and it is an essential step to develop module components that integrate functions on oyster metabolism relevant 
to bay water quality.

# Methodology
My research added two ROMS Fortran modules: one of them quantifies oyster physiological processes covered by Koojiman's Dynamic Energy 
Budget (DEB) model, and the other manages the progression of all the physiological states over time. Here, ROMS is a 
collective determining the biogeochemical features of a coupled model, COAWST. The latter was simulated with the added oyster 
modules, and the resulting NetCDF file had relevant data extracted and processed as presentable data through Python scripts.

# Key Findings
[Show (1) plankton data and (2) meat yield graphs.]

!Figure 1(/images/plankton_10m_3.0x_2023-07-19T09-00-00.png)
!Figure 2(/images/meat_yield_graph.png)

# Technical Details
- **Language:** Python/Fortran
- **Frameworks:** [e.g., NumPy, NetCDF4]
- **HPC/Compute:** [e.g., Local cluster / Cloud]
