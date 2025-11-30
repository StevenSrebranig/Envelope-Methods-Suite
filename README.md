# Envelope Methods Suite

The Envelope Methods Suite provides a unified overview of four lightweight, interpretable frameworks for dynamic systems: drift detection, statistical-envelope stability, equilibrium allocation, and decision coherence.

These methods form a cohesive toolkit:

- **HCM – Histogram Confidence Method**  
- **SECL – Statistical-Envelope Control Loops**  
- **MEO / Opportunity Optimization**  
- **WCS/DR – Weighted Cohesion Score & Dissolution Risk**

Each method is designed for conceptual clarity, robustness, and minimal computational overhead. Together they provide primitives for detecting drift, maintaining stability, allocating resources, and evaluating option coherence.

---

## 1. HCM – Histogram Confidence Method  
Real-time, nonparametric drift detection using adaptive histograms and precomputed confidence bounds.  
**DOI:** 10.5281/zenodo.17765246  
**GitHub:** https://github.com/StevenSrebranig/HCM

---

## 2. SECL – Statistical-Envelope Control Loops  
A distribution-bound control architecture that stabilizes drift-prone systems without fixed targets.  
**DOI:** 10.5281/zenodo.17715671  
**GitHub:** https://github.com/StevenSrebranig/SECL

---

## 3. MEO / Opportunity Optimization  
An equilibrium-seeking resource allocator based on marginal utility, marginal cost, and dynamic opportunity cost.  
**DOI:** 10.5281/zenodo.17705719  
**GitHub:** https://github.com/StevenSrebranig/MEO

---

## 4. WCS/DR – Weighted Cohesion Score & Dissolution Risk  
A decision-coherence framework for evaluating future-self alignment and structural stability across options.  
**DOI:** 10.5281/zenodo.17691769  
**GitHub:** https://github.com/StevenSrebranig/WCS-DR

---

## Conceptual Map

```
             +------------------+
             |       SECL       |
             |  Stabilize flow  |
             +---------+--------+
                       |
                       v
  +--------------+   +----------+   +------------------+
  |     HCM      |   |  MEO/OO  |   |      WCS/DR      |
  | Detect drift |-->| Allocate |-->| Evaluate options |
  +--------------+   +----------+   +------------------+
```

HCM monitors change.  
SECL maintains stability.  
MEO/OO allocates resources under equilibrium.  
WCS/DR compares options for coherence and dissolution risk.

---

## License  
MIT License — free for commercial and noncommercial use with attribution.

---

## Author  
**Steven F. Srebranig**  
Independent researcher integrating engineering, decision theory, and cognitive modeling.

```bibtex
@misc{Srebranig_2025_EnvelopeMethodsSuite,
  author       = {Srebranig, Steven F.},
  title        = {Envelope Methods Suite — One-Page Overview},
  year         = 2025,
  doi          = {10.5281/zenodo.17766451},
  url          = {https://doi.org/10.5281/zenodo.17766451},
  publisher    = {Zenodo},
}
```

