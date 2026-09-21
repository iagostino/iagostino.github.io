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
LinkedIn: [isabelagostino](https://www.linkedin.com/in/isabelagostino/) | GitHub: [iagostino](https://github.com/iagostino) 

---

## Experience

### NASA Ames Research Center, Intelligent Systems Division
**OSTEM Intern**  
2026 (Summer) — Mountain View, CA  

- Developed a new route-planning capability, [`PathPlannerBase`](https://github.com/nasa/fmdtools/blob/main/src/fmdtools/define/pathplan.py, for modeling autonomous system resilience and behavior under degraded conditions.
- Performed unit and integration testing to support package inclusion in [`fmdtools` v2.5.0](https://github.com/nasa/fmdtools/releases/tag/v2.5.0).
- Authored  documentation and examples to improve public access in line with NASA's open science goals.

<!-- Developed a new path-planning class and supporting functionality for fmdtools, a Python library for fault modeling and evaluation, improving its ability to simulate autonomous system behavior under degraded conditions. -->
<!-- Integrated custom path-planning methods into existing fmdtools workflows, enabling smoother interaction between fault modeling, system behavior representation, and route generation. -->
<!-- Designed and executed thorough unit and integration tests to validate algorithm performance, ensure numerical stability, and verify compatibility with the broader library ecosystem. -->
<!-- Collaborated with mentors and researchers to refine requirements, troubleshoot unexpected behavior, and iterate on design choices to support future modeling capabilities. -->




### West Monroe Partners
**Consultant & Business Analyst**  
2022–2023 — Tysons, VA  

- Automated financial reporting workflows via data-processing pipelines, reducing manual effort and errors.
- Translated client negotiations into precise contract revisions, ensuring business requirements were accurately documented and mutually understood by all stakeholders.

<!-- Automated financial reporting workflows, reducing manual error rates and processing time  -->
<!-- Built structured data validation and querying tools for improved analytical reliability -->
<!-- Standardized data workflows across teams and clients -->
<!-- Produced documentation and process guides for long-term maintainability -->



### National Institute of Standards and Technology (NIST)
**Summer Undergraduate Research Fellow**  
Summer 2021 — Gaithersburg, MD  

- Developed a scalable genetic algorithm for evaluating the  uniformity (star discrepancy) of high-dimensional quasi-random sequences.
- Evaluated convergence and computational efficiency against existing algorithms and theoretical benchmarks.

<!-- Developed a genetic algorithm to approximate star discrepancy in high-dimensional sequences -->
<!-- Evaluated convergence behavior, efficiency, and solution quality -->
<!-- Benchmarked heuristic performance against theoretical methods -->

---

## Education

### University of California, Berkeley
**Ph.D., Industrial Engineering & Operations Research**  
2024–2028 (expected) — Berkeley, CA  

- Advisor: Dr. Thibaut Mastrolia
- Developed mathematical models to optimize investment decisions for critical energy infrastructure under uncertainty and cyber threats, enabling evaluation of risk-management strategies.
- Built and analyzed efficient Markov chain approximation algorithms, with novel Hawkes process discretization, that made otherwise intractable decision problems computationally feasible.
- Developed stochastic model using new It\^o calculus techniques to address energy demand-response contracting under uncertain customer behavior and random service disruptions.

  
<!-- Formulated and solved a singular-stopping stochastic control problem with self-exciting (Hawkes) jump dynamics via a variational HJB equation with gradient constraints.
<!-- Built a discrete-time Markov chain approximation (with a novel Hawkes-process discretization) and proved its value function converges to the continuous-time control problem, then validated the theory with Monte Carlo simulations in Python.
- Developing BSDE/2BSDE techniques for mean-field contract theory under common noise and jump risk, including new Itô calculus for two coupled flows of conditional measures.-->



### University of California, Berkeley
**M.S., Industrial Engineering & Operations Research**  
2023–2024 — Berkeley, CA  

- Worked with Dr. Alper Atamtürk on Resilient Logistics (U.S. Department of Defense, Office of Naval Research).
- Designed and built optimization models to evaluate how multi-stage supply chains could continue operating under disruptions and operational hazards.
- Formulated and solved large-scale constrained routing and scheduling problems to enable comparison of logistics strategies before committing resources.
- Contributed  user-friendly back-end analytics components to a decision-support tool used for operational planning.

  
<!-- Designed and implemented large-scale, constraint-intensive optimization models for multi-stage supply chain routing and scheduling.-->
<!-- Developed stochastic and scenario-based models for uncertainty in demand, transit times, and system disruptions.-->
<!-- Built scalable algorithms for high-dimensional routing and scheduling problems -->
<!-- Contributed to decision-support tools for logistics planning, visualization, and reporting -->


### William & Mary
**B.S., Mathematics (Minor: Economics)**  
2018–2022 — Williamsburg, VA  

- Thesis: Approximating Star-Discrepancy with a Genetic Algorithm  
- Graduated summa cum laude and Phi Beta Kappa with departmental honors.  

---

## Selected Honors

- [Outstanding Graduate Student Instructor Award](https://gsi.berkeley.edu/programs-services/award-programs/ogsi/) (2026)  
- UC Berkeley Chancellor’s Fellowship (2024)
- [Phi Beta Kappa](https://www.wm.edu/sites/pbk/selectionprocess/), Alpha Chapter of Virginia (2022)
- [Departmental Honors](https://www.wm.edu/as/mathematics/research/undergraduate_research/honors/), William & Mary Department of Mathematics (2022)
- [James Monroe Scholars Program](https://www.wm.edu/as/monroescholars/) (2018)  

---

## Skills

**Languages:** Python, Julia, R, SQL, MATLAB, VBA
**Optimization:** Gurobi, Pyomo, CVXPY, linear & nonlinear optimization, dynamic programming, Monte Carlo simulation
**Scientific Computing:** NumPy, SciPy, pandas, scikit-learn, Numba, Git
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
  
