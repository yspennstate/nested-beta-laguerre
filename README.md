# Nested beta-Laguerre ensembles

Yitzchak Shmalo

The paper (`main.tex`, `main.pdf`) answers the Laguerre case of Question 2 in Virág's ICM 2014 survey *Operator limits of random matrices* (arXiv:1804.06953): is there one Jacobi matrix whose leading n x n block has the beta-Laguerre eigenvalue law for every n?

For beta > 0 and a > -1, let B be lower bidiagonal with independent entries

    B_ii = beta^(-1/2) chi_{beta(a+i)},   B_{i+1,i} = beta^(-1/2) chi_{beta i}.

Then L = B B^T is a Jacobi matrix, and its leading block L_n has eigenvalue density proportional to

    Delta(x)^beta  prod_j x_j^(theta(a+1)-1) exp(-theta x_j),   theta = beta/2,

for every n at once. The proof reverses and transposes the Dumitriu–Edelman bidiagonal model. L is almost surely essentially self-adjoint, so the spectral measure at the first coordinate is one random measure whose degree-n orthogonal polynomial has the n-point Laguerre zero law for all n. The antisymmetric Gaussian beta ensemble of Dumitriu and Forrester nests in the same way.

The paper also proves several obstructions under stated hypotheses: no absolutely continuous full corners law for tridiagonal matrices, the parameter shift of the ordinary Dixon–Anderson link, the failure of the reversed Killip–Nenciu Jacobi model, the triviality of unitary principal-block chains, and two Gaussian characterisations.

The paper is part of the Math Brain project: https://github.com/yspennstate/math-brain-public

## Files

- `main.tex`: LaTeX source (amsart)
- `main.pdf`: compiled paper, 8 pages
