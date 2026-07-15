---
title: "Shizugawa Bay Biogeochemical Modelling"
excerpt: "Developed an add-on module to analyse the effects of Shizugawa Bay oysters on bay water quality."
collection: portfolio
---

# Scientific Challenge
Shizugawa Bay is a significant source of seafood for Japan's market. Recent data indicates observed hypoxia 
around oyster raft areas developing during summer. A coupled biogeochemical model aimed at 
diagnosing factors tied to rearing aquaculture, including water quality and economic profitability, 
has been in development, and it is an essential step to develop module components that integrate functions 
on oyster metabolism relevant to bay water quality.

# Methodology
My research added two ROMS Fortran modules: one of them quantifies oyster physiological processes covered by Koojiman's Dynamic Energy 
Budget (DEB) model, and the other manages the progression of all the physiological states over time. Here, ROMS is a 
collective determining the biogeochemical features of a coupled model, COAWST. The latter was simulated with the added oyster 
modules, and the resulting NetCDF file had relevant data extracted and processed as presentable data through Python scripts.

# Key Findings
Model simulations show increasing drops in plankton count at the lowest-density portions of Shizugawa Bay as oyster farm rope density 
increases. [Change the figure to four frames from the same time, but from different density cases.]

![Figure 1](/images/plankton_10m_3.0x_2023-07-19T09-00-00.png)

Oyster meat yield per individual data 30 days after juvenile oyster situation was also collected, 
relevant for future work on market profitability analysis beneficial for farmers working at the area.

![Figure 2](/images/meat_yield_graph.png)

# Technical Details
- **Language:** Python/Fortran
- **Frameworks:** [e.g., NumPy, NetCDF4]
- **HPC/Compute:** [e.g., Local cluster / Cloud]
