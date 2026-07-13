# O30 — Born–Infeld Parity Forces an Equatorial Admissible Fibre

This repository contains the source of the **O30 Cosmochrony paper**
*Born–Infeld Parity Forces an Equatorial Admissible Fibre: Analytical Derivation
of the $[1:\tfrac{1}{2}:\tfrac{1}{2}]$ Eigenvalue Ratio*.

Papers O28–O29 established that the per-pair covariance $\mathcal{C}_c$ in
$\operatorname{Sym}^2(V_\rho)$ has rank $r_{\mathrm{eff}} = 3$ with the invariant
eigenvalue structure $[\lambda_1:\lambda_2:\lambda_3] = [1:\tfrac12:\tfrac12]$, and
flagged the origin of this ratio as an open problem. **This paper gives the complete
analytical derivation.**

## Core Result

The ratio $\lambda_1/\lambda_2 = 2$ is **not dynamical and not statistical, but purely
structural** — a consequence of three compatible structures: Born–Infeld (BI) parity,
the $\operatorname{Sym}^2(V_\rho)$ identification, and the Heisenberg grading.

The BI parity anti-linearity $\rho_{q-c} = \bar\rho_c$ (O18) forces every admissible
square-root coordinate $w_j \in V_\rho \cong \mathbb{C}^2$ to satisfy $|\alpha_j| = |\beta_j|$
— the **equatorial constraint**: each $w_j$ lives on an equatorial $S^1 \subset S^3$, with
$w_j = (r_j/\sqrt2)(e^{i\phi_j}v_+ + e^{-i\phi_j}v_-)$. In this regime the central component
of $\operatorname{vec}(M_j)$ is phase-independent while the diagonal components oscillate as
$e^{\pm 2i\phi_j}$, which fixes the covariance spectrum to $[1:\tfrac12:\tfrac12]$.

## Keywords

Born–Infeld parity, Weil representation, symmetric square, Heisenberg grading,
admissible fibre, covariance spectrum, spectral admissibility.

## Repository Contents

```
o30/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (Spectral-O30.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.20014707](https://doi.org/10.5281/zenodo.20014707)
- 🌐 Website: https://cosmochrony.org/science/spectral/program/o30/

## Citation

> J. Beau, *Born–Infeld Parity Forces an Equatorial Admissible Fibre: Analytical
> Derivation of the $[1:\tfrac{1}{2}:\tfrac{1}{2}]$ Eigenvalue Ratio*, Zenodo, 2026.
> DOI: 10.5281/zenodo.20014707.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
