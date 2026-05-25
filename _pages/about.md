---
permalink: /
title: "Lin Zhicheng"
excerpt: "Undergraduate student in Computer Science and Technology at Jimei University, working on computer vision, image signal processing, and scientific AI workflows."
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

I am an undergraduate student majoring in Computer Science and Technology at [Jimei University](https://www.jmu.edu.cn/). My current work focuses on computer vision, image signal processing, graph/topology-aware algorithms, and AI-agent workflows for scientific research.

I am especially interested in building reliable systems that connect algorithms with real experimental needs, including microscopic image analysis, cell lineage reconstruction, ISP enhancement, multimodal data processing, and automated research pipelines.

Email: [202321331023@jmu.edu.cn](mailto:202321331023@jmu.edu.cn) &nbsp;|&nbsp; GitHub: [Ac157OL](https://github.com/Ac157OL) &nbsp;|&nbsp; CSDN: [Ac157ol](https://blog.csdn.net/Ac157ol)

# News
- *2026.05*: Awarded the Provincial Third Prize in the 13th National College Students' New Generation Information Communication Technology Competition.
- *2025.10*: Awarded the Provincial Third Prize in the National College Students Mathematical Modeling Competition.
- *2025.06*: Awarded the National Scholarship for the 2024-2025 academic year.
- *2025.06*: Won the National Second Prize A in the 1st National Artificial Intelligence Application Innovation Competition.
- *2025.05*: Won the National First Prize in the 2nd GOSIM Global Hackathon Programming Competition.

# Research Projects

## TopoInherit: Cell Lineage Reconstruction for *Pyropia haitanensis*
*2024.09 - Present*

This project studies robust spatiotemporal matching and tracking algorithms for dense honeycomb-like algal cell populations under time-lapse microscopy. The core challenge is to reconstruct cell lineage relationships despite field-of-view drift, intermittent ex-vivo observation, long 24-hour imaging intervals, and topology changes caused by cell proliferation.

- Proposed **TopoInherit**, a cell lineage reconstruction framework that combines local topological features with environmental evidence chains, global-priority arbitration, and adaptive topology consistency validation. The method achieved an F1 score of **92.26%** for lineage relationship prediction.
- Developed a 2D physical simulation and analysis tool for cellular tissues, supporting regular hexagonal grids, randomly sized cell morphology generation, topology-change simulation, proliferation modeling, real-time rendering, and geometric computation.
- Led the development of **CeL3Label**, a precise annotation tool for cell lineage labeling, and built two expert-level annotated datasets for *Pyropia haitanensis* cell tracking.
- Designed a self-developed Skill workflow on the WorkBuddy platform, connecting natural-language instructions with cloud algorithms and large models to support an end-to-end loop of image tracking, intelligent retrieval, and report generation.
- Served as project leader for a National College Students Innovation and Entrepreneurship Training Program project, which has been successfully completed.

## Intelligent Image Signal Enhancement and Adaptive Parameter Mechanisms
*2025.04 - 2025.12*

Participated in the design of an Image Signal Processor (ISP) project and worked on image signal optimization algorithms and deployment. The project strengthened my practical experience in computer vision, machine learning, deep learning, image enhancement, and algorithm engineering.

- Developed and evaluated adaptive enhancement algorithms for improving image signal quality and processing efficiency.
- Published the conference paper **"Adaptive Gamma Correction with Explicitly Nonlinear Balancing"** as the second author at **ICSPS 2025**.

# Publications

- **Adaptive Gamma Correction with Explicitly Nonlinear Balancing**. **Lin Zhicheng** (second author), et al. **ICSPS 2025**.
- **TopoInherit: Robust Cell Lineage Reconstruction in Rigid Algal Networks via Neighborhood Topological Inheritance under Long-term Intervals and FOV Fluctuations**. **Lin Zhicheng** (first author), et al. Submitted to **PLOS Computational Biology**.
- **TCPCN: Topology-Constrained Polygonization for Cellular Networks under Microscopic Imaging of Dense Honeycomb-like Plant Tissues**. **Lin Zhicheng** (second author), et al. Submitted to **Journal of Microscopy**.

# Competitions

- *2025.05*: National First Prize, 2nd GOSIM Global Hackathon Programming Competition. Reproduced the PikaRAG knowledge-enhanced model and developed an automated CLI interaction tool based on the MoFA framework for one-click construction and scheduling of multi-agent data flows.
- *2025.06*: National Second Prize A, 1st National Artificial Intelligence Application Innovation Competition. Cooperated with KingKungfu (Xiamen) Information Technology Co., Ltd.; worked on vertical-domain data cleaning, instruction set construction, and LoRA-based knowledge injection for large models.
- *2025.06*: Provincial First Prize A, 11th National College Students Statistical Modeling Competition, Fujian Division. Built a UAV-view action recognition pipeline using OpenPose for 2D keypoint extraction, 2D-to-3D pose reconstruction, and temporal-spatial models including CTR-GCN and SkateFormer.
- *2025.06*: Provincial Second Prize, 18th Chinese Collegiate Computing Competition.
- *2024.12*: Provincial Second Prize, Huawei ICT Competition China Practice Competition, Ascend AI Track.
- *2024.04*: National Third Prize, 15th Lanqiao Cup C/C++ Programming Contest, University Group B.
- *2024.11*: Provincial Third Prize, 6th Global Campus AI Algorithm Elite Competition.
- *2025.06*: Provincial Third Prize, 7th Global Campus AI Algorithm Elite Competition.
- *2025.10*: Provincial Third Prize, National College Students Mathematical Modeling Competition.
- *2026.05*: Provincial Third Prize, 13th National College Students' New Generation Information Communication Technology Competition.

# Honors and Awards

- *2025.06*: National Scholarship, 2024-2025 academic year.
- *2024.11*: Tan Kah Kee Scholarship, 2023-2024 academic year.
- First-class Scholarship, Jimei University, awarded 5 times.
- Merit Student, Jimei University.
- Outstanding Communist Youth League Cadre.
- CET-6; Huawei Certified ICT Professional - AI (HCIP-AI); Putonghua Proficiency Test, Grade 2-A.

# Education

- *2023.09 - Present*: B.Eng. in Computer Science and Technology, Jimei University.
- GPA: **4.22/5.0**; Rank: **1/125**.

# Skills and Interests

- Research areas: computer vision, microscopic image analysis, graph/topology-aware modeling, image signal processing, machine learning, deep learning, scientific AI workflows.
- Engineering experience: Python/C/C++, algorithm simulation, data annotation tools, CLI automation, multi-agent workflows, LoRA fine-tuning, OpenPose, CTR-GCN, SkateFormer.
