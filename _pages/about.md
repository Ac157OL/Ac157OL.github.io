---
permalink: /
title: "Lin Zhicheng"
excerpt: "Junior undergraduate student in Computer Science and Technology at Jimei University, working on computer vision, object detection, LiDAR and point-cloud perception, 3D reconstruction, and large language models."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div class="intro-panel" markdown="1">

I am a junior undergraduate student majoring in Computer Science and Technology at [Jimei University](https://www.jmu.edu.cn/), advised by Prof. Bin Huang. My current work focuses on computer vision, object detection and classification in LiDAR/point-cloud perception, instance segmentation, 3D reconstruction, image signal processing, graph/topology-aware algorithms, and large language model research.

I am especially interested in two research directions: computer vision, including object detection, point-cloud and LiDAR perception, 3D reconstruction, and instance segmentation; and large language model research, especially multimodal interaction with LLMs and vision-language-action (VLA) systems. **I expect to be eligible for recommendation-based graduate admission and am actively seeking prospective graduate supervisors and research opportunities.**

<div class="research-tags">
  <span><i class="fas fa-eye" aria-hidden="true"></i> Computer Vision</span>
  <span><i class="fas fa-bullseye" aria-hidden="true"></i> LiDAR Perception</span>
  <span><i class="fas fa-cubes" aria-hidden="true"></i> 3D Reconstruction</span>
  <span><i class="fas fa-comments" aria-hidden="true"></i> Multimodal LLMs</span>
</div>

Email: [202321331023@jmu.edu.cn](mailto:202321331023@jmu.edu.cn) &nbsp;|&nbsp; GitHub: [Ac157OL](https://github.com/Ac157OL) &nbsp;|&nbsp; CSDN: [Ac157ol](https://blog.csdn.net/Ac157ol)

</div>

<span class='anchor section-anchor' id='education'></span>

<h1><i class="fas fa-graduation-cap section-heading-icon" aria-hidden="true"></i> Education</h1>

<div class="status-strip" markdown="1">
**Current status:** Junior undergraduate student expecting recommendation-based graduate admission and seeking prospective graduate supervisors in computer vision, 3D perception, and large language model research.
</div>

- *2023.09 - Present*: B.Eng. in Computer Science and Technology, Jimei University.
- GPA: **4.22/5.0**; Rank: **1/125**.

<span class='anchor section-anchor' id='news'></span>

<h1><i class="fas fa-bullhorn section-heading-icon" aria-hidden="true"></i> News</h1>
- *Present*: **Expecting recommendation-based graduate admission and seeking prospective graduate supervisors in computer vision, 3D perception, and large language model research.**
- *Present*: Exploring object detection, classification, and instance segmentation for LiDAR and point-cloud perception.
- *Present*: Continuing research on topology-aware microscopic image analysis and robust cell lineage reconstruction.
- *Present*: Developing AI-assisted scientific workflows that connect visual perception algorithms with practical research tasks.

<span class='anchor section-anchor' id='research'></span>

<h1><i class="fas fa-flask section-heading-icon" aria-hidden="true"></i> Research Projects</h1>

## TopoInherit: Cell Lineage Reconstruction for *Pyropia haitanensis*
*2024.09 - Present*

Repository: [Ac157OL/TopoInherit](https://github.com/Ac157OL/TopoInherit)

This project studies robust spatiotemporal matching and tracking algorithms for dense honeycomb-like algal cell populations under time-lapse microscopy. The core challenge is to reconstruct cell lineage relationships despite field-of-view drift, intermittent ex-vivo observation, long 24-hour imaging intervals, and topology changes caused by cell proliferation.

- Proposed **TopoInherit**, a cell lineage reconstruction framework that combines local topological features with environmental evidence chains, global-priority arbitration, and adaptive topology consistency validation. The method achieved an F1 score of **92.26%** for lineage relationship prediction.
- Developed a 2D physical simulation and analysis tool for cellular tissues, supporting regular hexagonal grids, randomly sized cell morphology generation, topology-change simulation, proliferation modeling, real-time rendering, and geometric computation.
- Led the development of [**CeL3Label**](https://github.com/Ac157OL/Ce3Label), a precise annotation tool for cell lineage labeling, and built two expert-level annotated datasets for *Pyropia haitanensis* cell tracking, available on [Zenodo](https://doi.org/10.5281/zenodo.19571835).
- Designed a self-developed [Skill workflow](https://github.com/Ac157OL/cell-skills) on the WorkBuddy platform, connecting natural-language instructions with cloud algorithms and large language models to support an end-to-end loop of image tracking, intelligent retrieval, and report generation.
- Served as project leader for a National College Students Innovation and Entrepreneurship Training Program project, which has been successfully completed.

## Intelligent Image Signal Enhancement and Adaptive Parameter Mechanisms
*2025.04 - 2025.12*

Participated in the design of an Image Signal Processor (ISP) project and worked on image signal optimization algorithms and deployment. The project strengthened my practical experience in computer vision, machine learning, deep learning, image enhancement, and algorithm engineering.

- Developed and evaluated adaptive enhancement algorithms for improving image signal quality and processing efficiency.
- Published the conference paper **"Adaptive Gamma Correction with Explicitly Nonlinear Balancing"** as the second author at **ICSPS 2025**.

<span class='anchor section-anchor' id='publications'></span>

<h1><i class="fas fa-file-alt section-heading-icon" aria-hidden="true"></i> Publications</h1>

<div class="publication-list" markdown="1">

<div class="publication-card" markdown="1">
**Adaptive Gamma Correction with Explicitly Nonlinear Balancing**<br>
**Lin Zhicheng** (second author), et al. **ICSPS 2025**.
</div>

<div class="publication-card" markdown="1">
**TopoInherit: Robust Cell Lineage Reconstruction in Rigid Algal Networks via Neighborhood Topological Inheritance under Long-term Intervals and FOV Fluctuations**<br>
**Lin Zhicheng** (first author), et al. Submitted to **PLOS Computational Biology**.

Repository: [Ac157OL/TopoInherit](https://github.com/Ac157OL/TopoInherit)

<figure class="workflow-figure">
  <img src="{{ '/images/TopoInherit.png' | relative_url }}" alt="TopoInherit workflow for robust cell lineage reconstruction">
  <figcaption>Workflow of the TopoInherit cell lineage reconstruction framework.</figcaption>
</figure>
</div>

<div class="publication-card" markdown="1">
**TCPCN: Topology-Constrained Polygonization for Cellular Networks under Microscopic Imaging of Dense Honeycomb-like Plant Tissues**<br>
**Lin Zhicheng** (second author), et al. Submitted to **Journal of Microscopy**.

Repository: [Vicky-quq/TCPNC](https://github.com/Vicky-quq/TCPNC)

<figure class="workflow-figure">
  <img src="{{ '/images/TCPCN.png' | relative_url }}" alt="TCPCN workflow for topology-constrained polygonization">
  <figcaption>Workflow of the TCPCN topology-constrained cellular network polygonization method.</figcaption>
</figure>
</div>

</div>

<span class='anchor section-anchor' id='competitions'></span>

<h1><i class="fas fa-trophy section-heading-icon" aria-hidden="true"></i> Competitions</h1>

- *2025.05*: National First Prize, 2nd GOSIM Global Hackathon Programming Competition. Reproduced the PikaRAG knowledge-enhanced model and developed an automated CLI interaction tool based on the MoFA framework for one-click construction and scheduling of multi-agent data flows.
- *2025.06*: National Second Prize A, 1st National Artificial Intelligence Application Innovation Competition. Cooperated with KingKungfu (Xiamen) Information Technology Co., Ltd.; worked on vertical-domain data cleaning, instruction set construction, and LoRA-based knowledge injection for large language models.
- *2025.06*: Provincial First Prize A, 11th National College Students Statistical Modeling Competition, Fujian Division. Built a UAV-view action recognition pipeline involving 2D keypoint extraction, 2D-to-3D pose reconstruction, and deep spatiotemporal recognition algorithms.
- *2025.06*: Provincial Second Prize, 18th Chinese Collegiate Computing Competition.
- *2024.12*: Provincial Second Prize, Huawei ICT Competition China Practice Competition, Ascend AI Track.
- *2024.04*: National Third Prize, 15th Lanqiao Cup C/C++ Programming Contest, University Group B.
- *2024.11*: Provincial Third Prize, 6th Global Campus AI Algorithm Elite Competition.
- *2025.06*: Provincial Third Prize, 7th Global Campus AI Algorithm Elite Competition.
- *2025.10*: Provincial Third Prize, National College Students Mathematical Modeling Competition.
- *2026.05*: Provincial Third Prize, 13th National College Students' New Generation Information Communication Technology Competition.

<span class='anchor section-anchor' id='honors'></span>

<h1><i class="fas fa-award section-heading-icon" aria-hidden="true"></i> Honors and Awards</h1>

- *2025.06*: National Scholarship, 2024-2025 academic year.
- *2024.11*: Tan Kah Kee Scholarship, 2023-2024 academic year.
- First-class Scholarship, Jimei University, awarded 5 times.
- Merit Student, Jimei University.
- Outstanding Communist Youth League Cadre.
- CET-6; Huawei Certified ICT Professional - AI (HCIP-AI); Putonghua Proficiency Test, Grade 2-A.

<span class='anchor section-anchor' id='skills'></span>

<h1><i class="fas fa-tools section-heading-icon" aria-hidden="true"></i> Skills and Interests</h1>

- Research areas: computer vision, object detection, LiDAR and point-cloud perception, 3D reconstruction, instance segmentation, microscopic image analysis, graph/topology-aware modeling, image signal processing, deep learning, large language models, multimodal LLMs, and VLA systems.
- Engineering experience: Python/C/C++, deep learning algorithm development, computer vision pipelines, 3D perception workflows, algorithm simulation, data annotation tools, CLI automation, multi-agent workflows, and LoRA fine-tuning.
