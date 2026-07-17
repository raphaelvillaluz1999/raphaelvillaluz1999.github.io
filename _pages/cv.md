---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in Transdisciplinary Science and Engineering, Institute of Science Tokyo (formerly Tokyo Institute of Technology), 2026

Work experience
======
* F.Y. 2025-2026: Research Assistant
  * Institute of Science Tokyo
  * Duties includes: Developing a coupled model, and collecting data via fieldwork for Shizugawa Bay
  * Supervisor: Associate Professor Takashi Nakamura
  
Skills
======
* **Programming Languages**
  * Python (scientific computing & automation)
  * Fortran (ROMS core development)

* **Ocean & Biogeochemical Modeling**
  * COAWST-ROMS coupled model development
  * Coastal ecosystem process modeling
  * Model calibration, validation & sensitivity analysis

* **Scientific Data Analysis**
  * `xarray`, `xroms`, `pandas`, `numpy`
  * `netCDF4` multi-dimensional data I/O and manipulation

* **Data Pipeline & Sensor Integration**
  * Sensor data acquisition, cleaning and formatting
  * Automated CSV / Excel export with configurable axes (depth, time)
  * CLI tooling and file-system automation (`argparse`, `pathlib`, `glob`, `os`, `shutil`, `re`)

* **Scientific Visualisation**
  * `matplotlib` (publication-quality static figures)
  * Time-series animation and video rendering (`FFMpegWriter`)
  * Headless / HPC-optimized batch rendering (`matplotlib.use("Agg")`)

* **Workflow & Compute**
  * Reproducible analysis pipelines
  * Headless compute-optimised processing workflows

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
