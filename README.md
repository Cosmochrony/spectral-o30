# O30 — A Conditional 3×3 Model on Sym²(Vρ)

This repository contains version 2.0 of the O30 Cosmochrony paper,
*A Conditional 3×3 Model on Sym²(Vρ): Equatorial Fibres from a Fixed Symmetric Square,
and the Exact Decorrelation Conditions for its Spectrum*.

## Scope

O30 studies a conditional covariance model on `Sym²(Vρ) ≅ C³`. It is not the `9×9`
covariance on `End(H_eff)` measured in O28, and it does not derive the O28 spectrum.

The model assumes:

- (H0) the data lie on a Veronese cone of rank-one symmetric squares;
- (H1) a supplied inter-block identification;
- (H2) the exchanged anti-linear involution on the doublet;
- (H3) fixedness of the projected symmetric square.

Under (H0)–(H3), a square root satisfies
`β_j = ε_j conjugate(α_j)` with `ε_j ∈ {+1,−1}`. The exact diagonal spectrum
`[1:1/2:1/2]` additionally requires both weighted cancellations
`<ε r⁴ exp(2iφ)> = 0` and `<r⁴ exp(4iφ)> = 0`. Neither condition is derived or
measured in the cited corpus.

The factor of two in the diagonal entries comes from symmetric-tensor normalisation. The
Carnot grading identifies the central direction that carries the factor; it is not its algebraic
cause.

## Correction in version 2.0

Version 2.0 withdraws the former claim that Born–Infeld parity alone forces the equatorial fibre or
that O30 analytically explains O28. It separates the two covariance objects, states all load-bearing
hypotheses, carries both sign branches, uses one averaging convention, and gives the two exact
weighted decorrelation conditions.

## Repository contents

```text
o30/
├── tex/         # LaTeX source and bibliography
├── out/         # Compiled PDF
├── zenodo.json  # Zenodo release metadata
└── README.md
```

## Links

- DOI: [10.5281/zenodo.20014707](https://doi.org/10.5281/zenodo.20014707)
- Website: <https://cosmochrony.org/science/spectral/program/o30/>

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large language
models used as analytical assistants. All claims and final formulations remain the author's
responsibility.
