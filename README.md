# Million-Scale Max-3-SAT Solver
**Version**: v1 | **Published**: February 26, 2026 | **DOI**: [10.5281/zenodo.18787731](https://doi.org/10.5281/zenodo.18787731)

## Core Results
- **Scale**: 1,000,000 variables | 4,200,000 clauses
- **Performance**: 95.36% clause satisfaction (4,005,054/4,200,000) in **19.66 seconds** (single CPU core)
- **Diagnosis**: Extracts 4.6% Unsat Core (Active Dual Set) for industrial constraint debugging
- **Commit Timestamp**: bb953e1eb0d32c2b6cf38121f28209860e50465c

## Key Methodology
Powered by the **Equi-Efficiency Principle (EEP)** (Lagrangian dual equilibration), the solver achieves linear time complexity (O(n+m)) for 3-CNF formulas, with 159,819 primal flips and max dual deviation < 1e-3 at convergence.

## State-of-the-Art Comparison
| Solver       | 10⁵ Variables | 10⁶ Variables       |
|--------------|---------------|---------------------|
| MaxHS/Kissat | OOM (64GB RAM)| OOM (64GB RAM)      |
| WalkSAT      | 45s           | > 2 hours           |
| Our Solver   | 1.8s          | 19.66s (95.36%)     |

## Author
Yang, Dequan (Researcher)

## Citation
### APA 7th Edition
Yang, D. (2026). *Million-Scale Max-3-SAT Solver: Linear-Time Implementation with 95.36% Satisfaction* (Version v1) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.18787731

### BibTeX
```bibtex
@software{yang_2026_18787731,
  author       = {Yang, Dequan},
  title        = {Million-Scale Max-3-SAT Solver | EEP-Powered},
  month        = feb,
  year         = 2026,
  publisher    = {Zenodo},
  version      = {v1},
  doi          = {10.5281/zenodo.18787731},
  url          = {https://doi.org/10.5281/zenodo.18787731}
}
