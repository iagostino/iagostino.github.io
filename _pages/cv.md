---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Isabel Agostino

**Ph.D. Candidate in Industrial Engineering & Operations Research**  
Berkeley, CA  
📧 iagostino@berkeley.edu  
🌐 https://iagostino.github.io  
LinkedIn: isabelagostino | GitHub: iagostino  

---

## Education

### University of California, Berkeley
**Ph.D., Industrial Engineering & Operations Research**  
2024–2028 (expected) — Berkeley, CA  

- Advisor: Dr. Thibaut Mastrolia  
- Formulated and solved a singular-stopping stochastic control problem with self-exciting (Hawkes) jump dynamics via a variational HJB equation with gradient constraints.
- Built a discrete-time Markov chain approximation (with a novel Hawkes-process discretization) and proved its value function converges to the continuous-time control problem, then validated the theory with Monte Carlo simulations in Python.
- Developing BSDE/2BSDE techniques for mean-field contract theory under common noise and jump risk, including new Itô calculus for two coupled flows of conditional measures.


---

### University of California, Berkeley
**M.S., Industrial Engineering & Operations Research**  
2023–2024 — Berkeley, CA  

- Worked with Dr. Alper Atamtürk on Resilient Logistics (U.S. Department of Defense, Office of Naval Research).
- Designed and implemented large-scale, constraint-intensive optimization models for multi-stage supply chain routing and scheduling; incorporated operational, capacity, timing, and resource constraints across distributed logistics networks.
- Developed stochastic and scenario-based modeling components to account for uncertainty in demand, transit times, and system disruptions.
- Contributed to the development of a deployable decision-support tool, including visualization and reporting components, to support data-driven logistics planning for end users.

  
<!-- Designed and implemented large-scale, constraint-intensive optimization models for multi-stage supply chain routing and scheduling.-->
<!-- Developed stochastic and scenario-based models for uncertainty in demand, transit times, and system disruptions.-->
<!-- Built scalable algorithms for high-dimensional routing and scheduling problems -->
<!-- Contributed to decision-support tools for logistics planning, visualization, and reporting -->

---

### William & Mary
**B.S., Mathematics (Minor: Economics)**  
2018–2022 — Williamsburg, VA  

- Thesis: Approximating Star-Discrepancy with a Genetic Algorithm  
- Graduated summa cum laude and Phi Beta Kappa with departmental honors.  

---

## Experience

### NASA Ames Research Center
**OSTEM Intern**  
2026 (Summer) — Mountain View, CA  

- Developed a path-planning module for the \texttt{fmdtools} Python library, under review for inclusion in the next release.
- Integrated route-generation methods into existing workflows to enhance autonomous-system simulation under degraded conditions.
- Authored unit and integration tests to ensure numerical robustness and library compatibility, and prepared end‑user examples to support correct and transparent usage.

<!-- Developed a new path-planning class and supporting functionality for fmdtools, a Python library for fault modeling and evaluation, improving its ability to simulate autonomous system behavior under degraded conditions. -->
<!-- Integrated custom path-planning methods into existing fmdtools workflows, enabling smoother interaction between fault modeling, system behavior representation, and route generation. -->
<!-- Designed and executed thorough unit and integration tests to validate algorithm performance, ensure numerical stability, and verify compatibility with the broader library ecosystem. -->
<!-- Collaborated with mentors and researchers to refine requirements, troubleshoot unexpected behavior, and iterate on design choices to support future modeling capabilities. -->


---

### West Monroe Partners
**Consultant & Business Analyst**  
2022–2023 — Tysons, VA  

- Automated financial reporting workflows by developing data processing and validation pipelines, significantly reducing manual error rates and turnaround time.
- Designed structured data querying and validation tools to improve reliability, traceability, and reproducibility of analytical outputs.
- Standardized and documented data workflows to enhance transparency and ensure consistent execution across internal teams and client stakeholders.
- Delivered user-oriented documentation and process guides to support adoption and long-term maintainability of automated tools.

<!-- Automated financial reporting workflows, reducing manual error rates and processing time  -->
<!-- Built structured data validation and querying tools for improved analytical reliability -->
<!-- Standardized data workflows across teams and clients -->
<!-- Produced documentation and process guides for long-term maintainability -->

---

### National Institute of Standards and Technology (NIST)
**Summer Undergraduate Research Fellow**  
Summer 2021 — Gaithersburg, MD  

- Designed and implemented a scalable genetic algorithm to approximate star discrepancy in high-dimensional quasi-random sequences (an NP-hard optimization problem).
- Evaluated convergence behavior, computational efficiency, and approximation quality across high-dimensional test cases.
- Conducted statistical analysis of heuristic performance and benchmarked results against theoretical bounds and existing methods.

<!-- Developed a genetic algorithm to approximate star discrepancy in high-dimensional sequences -->
<!-- Evaluated convergence behavior, efficiency, and solution quality -->
<!-- Benchmarked heuristic performance against theoretical methods -->

---

## Selected Honors

- [Outstanding Graduate Student Instructor Award](https://gsi.berkeley.edu/programs-services/award-programs/ogsi/) (2026)  
- UC Berkeley Chancellor’s Fellowship (2024)
- [Phi Beta Kappa](https://www.wm.edu/sites/pbk/selectionprocess/), Alpha Chapter of Virginia (2022)
- [Departmental Honors](https://www.wm.edu/as/mathematics/research/undergraduate_research/honors/), William & Mary Department of Mathematics (2022)
- [James Monroe Scholars Program](https://www.wm.edu/as/monroescholars/) (2018)  

---

## Skills

**Languages:** Python, Julia, R, SQL, MATLAB  
**ML Frameworks:** PyTorch, scikit-learn, TensorFlow  

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
