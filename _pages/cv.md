---
layout: archive
title:
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Industry Experience
### Staff Software Engineer
*Palo Alto Networks (Jun 2026 - Present)*
* Chronosphere was acquired by Palo in early 2026. Continuing prior work under a new job title.

### Applied AI Researcher
*Chronosphere (Aug 2025 - Jun 2026)*
* Developed context-aware anomaly detection tools under limited and noisy data.
* Enabled timeseries as a modality for LLMs without retraining.
* Built production-ready models optimised for performance, inference speed and compute cost with PyTorch.

### Google Summer of Code Contributor
*NumFOCUS, PyMC (May 2025 - Sep 2025)*
* Contributed to the implementation of Integrated Nested Laplace Approximations (INLA) for the PyMC library (Bayesian ML). More info [here](https://summerofcode.withgoogle.com/programs/2025/projects/Djw07Zv0) and [here](https://www.pymc.io/blog/blog_gsoc_2025.html).
* Supervised by [Rob Zinkov (University of Oxford)](https://www.zinkov.com/about/), [Theo Rashid (Amazon)](https://theorashid.github.io/cv/) and [Colt Allen (PyMC Labs)](https://www.linkedin.com/in/coltallen-datascientist/).

### Simulation and Machine Learning Engineer
*Monash High Powered Rocketry (Apr 2022 - Feb 2025)*
* Led the research and development of ANDROMEDA, a data-driven tool which sped up fluid simulations from hours to minutes.
* Vice lead of the Dynamics section during the 2023-2024 management cycle.
  * Oversaw and managed section R&D projects.
  * Reported to CTO at technical meetings.
* Built and ran distributed pipelines on the MonARCH cluster.

---

# Research Experience
### ML/AI Research Intern
*Bureau of Meteorology (Dec 2024 - Aug 2025)*
* Investigated a novel approach which blends the interpretability of physics-informed methods with the performance of modern transformer pretraining techniques.
* Developed an architecture which significantly reduced the training and inference cost of gridded data inputs.
* Built and ran training and evaluation pipelines on the Gadi cluster at scale.

### Student Research Intern
*University of Melbourne (Nov 2022 - Mar 2025)*
* First author in empirical study reporting novel observations of heat fluxes in tropical cyclones.
* Made data analysis up to 48 times faster by introducing multithreading.

---

# Education
### BEng (Hons)
*Monash University (Feb 2022 - Nov 2026)*
* Major: Aerospace Engineering, Minor: Artificial Intelligence
* WAM: 82/100, GPA: 3.64/4.00 (High Distinction)
* Honours Thesis under A/Prof. Mehrtash Harandi and Riccardo Ali.
* Selected cohort rankings:
  * 3rd of ~200 in ENG2005 Advanced Engineering Mathematics.
  * 8th of 197 in ECE4179 Neural Networks and Deep Learning
  * 2nd of 57 in MAE3401 Aerodynamics 2
  * 5th of 42 in MAE3404 Flight Vehicle Dynamics
  * Top 5% in MEC3456 Engineering Computational Analysis

### University Extension Program (Physics)
*University of Melbourne, (Feb - Nov 2021)*
* Selected as one of around 20 students statewide based on academic performance to undertake two first year physics units during my final year of high school.
* H1 Honours (High Distinction).
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

# Competitions and Awards
### Charles Hoult Modelling and Simulation Award 2nd Place, 2023
* Internationally recognised for ANDROMEDA at the Spaceport America Cup.

### International Young Physicists' Tournament (IYPT), 2021
* Captain of the Australian team.
* Researched and presented on university-level theory including Lagrangian mechanics whilst  still in high school. 
* Directed team in research setting under a tight schedule. 

### Two-time ASO Physics Olympiad Distinction, 2020 and 2021
  
---

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
