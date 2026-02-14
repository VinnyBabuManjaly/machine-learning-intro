# Math Foundations for Machine Learning

A curated, practical collection of Jupyter notebooks covering the mathematical foundations commonly used in machine learning: linear algebra, calculus, probability, and statistics. The notebooks focus on worked examples, visualizations, and small exercises that reinforce conceptual understanding and practical computation using NumPy, Matplotlib, and SymPy.

This repository is structured to be used as a self-study guide or as supporting materials for introductory ML courses. The content is written with clarity and practical utility in mind.

---

## High-level goals

- Provide concise, example-driven explanations of core mathematical concepts used in ML.
- Show how to compute, visualize, and verify mathematical constructs using Python (NumPy, Matplotlib, SymPy, SciPy).
- Offer small exercises to reinforce learning and a reference list of sources per notebook where available.

---

## Repository structure

- `1_linear_algebra/`
  - `1_vectors.ipynb` — vector basics, visualization, operations, dot/cross products, projections, basis change.
  - `2_matrices.ipynb` — matrix arithmetic, transpose, identity matrix, scalar operations, matrix types.
  - `3_gaussian_elimination.ipynb` — solving linear systems, row reduction, pivoting.
  - `3_linear_transformations.ipynb` — (rotation, scaling, matrix as linear operator) visual examples.
  - `4_matrix_inverse.ipynb` — inverse matrices and their computation/interpretation.
  - `5_matrices_change_basis.ipynb` — change of basis, coordinates, basis matrices.
  - `6_orthogonal_matrix.ipynb` — orthogonality, orthogonal matrices and properties.
  - `7_gram_schmidt_process.ipynb` — orthogonalization algorithms and examples.
  - `8_eigenvalues_eigenvectors.ipynb` — eigen decomposition, geometric meaning, examples.
  - `9_change_to_eigenbasis.ipynb` — diagonalization and change to eigenbasis.
  - `10_matrix_decomposition.ipynb` — matrix factorizations and decompositions (SVD, LU, etc.).
  - `11_exercises.ipynb` — assorted practice problems and worked solutions.

- `2_ calculus/`
  - `1_functions_graphs.ipynb` — functions, plotting, domain & range, examples.
  - `2_derivatives.ipynb` — derivatives, symbolic vs numerical, partial derivatives.
  - `3_chain_rule.ipynb` — chain rule and applications.
  - `4_norms.ipynb` — vector norms, p-norms, interpretation in ML.
  - `5_exercises.ipynb` — calculus exercises.

- `3_probability_statistics/`
  - `1_distributions.ipynb` — probability distributions overview and properties.
  - `2_expectation_variance.ipynb` — expectation, variance, properties, examples.
  - `3_entropy.ipynb` — entropy and information-theoretic quantities.

---

## Key dependencies

The notebooks primarily use the Python scientific stack. Recommended minimal environment:

- Python 3.9+ (3.10 or later preferred)
- numpy
- matplotlib
- sympy (for symbolic calculus examples)
- scipy (for select linear algebra utilities)

A `requirements.txt` is not included in the repo; create one with:

```bash
pip install numpy matplotlib sympy scipy
```

Or pin exact versions by creating a `requirements.txt`:

```text
numpy
matplotlib
sympy
scipy
```

---


## Example learning paths

- Beginner: start with `1_vectors.ipynb`, `2_matrices.ipynb`, `1_functions_graphs.ipynb`, and `1_distributions.ipynb`.
- Intermediate: continue with `3_gaussian_elimination.ipynb`, `4_matrix_inverse.ipynb`, `2_derivatives.ipynb`, `2_expectation_variance.ipynb`.
- Advanced: read `8_eigenvalues_eigenvectors.ipynb`, `9_change_to_eigenbasis.ipynb`, and `10_matrix_decomposition.ipynb` (SVD, LU) for ML applications like PCA.

---

## Sources and references

- Each notebook contains a `# Sources:` section listing links and references consulted during writing. These are included inline in the notebooks and may not be comprehensive or perfectly accurate; they should be treated as a starting point for deeper study.

