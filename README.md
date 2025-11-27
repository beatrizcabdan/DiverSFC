# DiverSFC 🌀  
**Measuring Data Diversity After Dimensionality Reduction Using Space-Filling Curves**

**DiverSFC** is a research and analysis toolkit designed to measure **data diversity** in lower-dimensional embeddings.  
It leverages **space-filling curves (SFCs)** to map multi-dimensional data (mostly from the automotive domain) into a one-dimensional representation, enabling efficient diversity quantification and comparison between datasets or models.

This repository provides tools to:
- Apply **space-filling curve mappings** to embedded data.
  - **Hilbert Curve:** Strong locality preservation, ideal for structured embeddings.  
  - **Morton (Z-order):** Fast to compute, used in indexing and spatial databases.  
- Compute **diversity metrics** (e.g., entropy, coverage, dispersion) on the 1D SFC domain.

---

## CSP ranges 

CSP range for valid speeds and steering wheel angles (based on properties of real trajectory data):
![CSP range](https://github.com/beatrizcabdan/DiverSFC/blob/153a671edc8067e337ce1c9963075f856123eec1/illustrations/CSP_range2.gif)
First, samples with different speeds appear, then, different maximum steering wheel angles appear. This example illustrates the bit-shifting issue when measuring the distance between CSPs.

## Research Context

If you use this repository in academic work, please cite:
```bibtex
@software{diversfc2025,
  author = {Beatriz Cabrero-Daniel},
  title = {DiverSFC: Measuring Data Diversity via Space-Filling Curves},
  year = {2025},
  url = {https://github.com/beatrizcabdan/DiverSFC}
}
```
