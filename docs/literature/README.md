# Literature

This directory contains citations and reading guidance for the divergence-free
shifted boundary method project. BibTeX entries are in [references.bib](references.bib).
Third-party PDFs are kept locally and are not distributed with the repository.

## Core papers

| BibTeX key | Reference and access | Role in the project |
| --- | --- | --- |
| `main2018shifted` | Alex Main and Guglielmo Scovazzi (2018). *The shifted boundary method for embedded domain computations. Part I: Poisson and Stokes problems.* Journal of Computational Physics, 372, 972-995. [DOI](https://doi.org/10.1016/j.jcp.2017.10.026) | Starting point for surrogate boundaries, shifted boundary conditions, and the Poisson and Stokes formulations. |
| `colomes2021weighted` | Oriol Colomés, Alex Main, Léo Nouveau, and Guglielmo Scovazzi (2021). *A weighted Shifted Boundary Method for free surface flow problems.* Journal of Computational Physics, 424, 109837. [DOI](https://doi.org/10.1016/j.jcp.2020.109837) | Further reading from the project brief on volume weighting and pressure oscillations with moving boundaries. |
| `frachon2024divergence` | Thomas Frachon, Erik Nilsson, and Sara Zahedi (2024). *Divergence-free cut finite element methods for Stokes flow.* BIT Numerical Mathematics, 64, article 39. [DOI](https://doi.org/10.1007/s10543-024-01040-x); [author preprint](https://arxiv.org/abs/2304.14230) | Further reading from the project brief on divergence-free unfitted discretizations and boundary enforcement. CutFEM provides related ideas rather than an SBM formulation to copy directly. |

## FEM background

- `johnson1987fem`: Claes Johnson, *Numerical solution of partial differential
  equations by the finite element method*, Cambridge University Press (1987).
  [Library catalogue](https://search.worldcat.org/title/16985782).
  Background for weak formulations, finite element approximation, and error
  analysis. The bibliography cites the 1987 edition; the edition of the local
  scanned copy has not been verified.
- `wi4014lecture8`: WI4014TU, *Numerical Analysis for PDE's*, lecture 8.
  Function spaces, differential operators, functionals, and variational calculus.
- `wi4014lecture9`: Same course, lecture 9. Ritz method, self-adjoint operators,
  basis functions, and the one-dimensional Poisson problem.
- `wi4014lecture10`: Same course, lecture 10. General weak formulations, Galerkin
  methods, element matrices, and assembly.

The lecture slides are course materials: obtain them through the course learning
environment. Their title pages do not identify an author or year, so those fields
are omitted from the bibliography.

## Project brief

`cse2026project10` identifies the CSE Minor 2026 Project 10 proposal for courses
TW3715TU and TW3725TU. The project concerns a divergence-free extension of the
generalized/weighted shifted boundary method for moving-boundary Stokes flow.
The listed supervisors are Oriol Colomés and Shreyas Prashanth; the document does
not explicitly identify its authors. Obtain the brief through the course or
supervisors. Keep the PDF local unless permission for public distribution is
confirmed.

## Local PDFs

Create `docs/literature/local/` in your checkout and place lawfully obtained PDFs
there. Git ignores the entire folder, including extracted text and other local
reading artifacts. The folder is intentionally absent from a fresh clone until
you create it. No source PDFs are needed to run the project.

The current local filenames are:

| Source | Local filename |
| --- | --- |
| Original SBM paper | `The shifted boundary method for embedded domain computations. Part I Poisson and Stokes problems.pdf` |
| Johnson textbook | `johnson_numerical_solutions_of_pde_by_fem.pdf` |
| FEM lectures | `NA8.pdf`, `NA9.pdf`, `NA10.pdf` |
| Project brief | `CSE Minor 2026 - Project 10 - Stokes Flow - Colomes - Prashanth (1).pdf` |

PDFs placed directly in `docs/literature/` are also ignored as a precaution.
Links point to publisher records, a library catalogue, or an author preprint;
access to full text may require a university account.

## Reading notes and distribution

Commit your own reading notes as Markdown files next to this index. Cite the
BibTeX key and relevant section or page when explaining a result. Useful notes
record the problem being solved, assumptions, formulation, and implications for
our implementation. Write explanations in your own words; copying a paper into
Markdown does not remove its copyright restrictions.

Public availability and attribution alone do not establish permission to
redistribute a source. Before adding any third-party file, check the license of
that specific version or obtain permission from the rights holder. Record its
source, copyright holder, license, and required attribution if redistribution is
allowed. Any repository license for our work does not relicense third-party
material. See [TU Delft's copyright notice](https://repository.tudelft.nl/record/uuid%3Af116c1eb-35ca-4ecb-a58f-37ae764280e8)
and the [Creative Commons FAQ](https://creativecommons.org/faq/).

Ignore rules do not remove files already tracked by Git or erase earlier commits.
Check the files being committed before publishing.
