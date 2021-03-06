# Linear Algebra
A quick glance over basic linear algebra topics.

1. [Vectors and Spaces](https://github.com/kkufieta/linear-algebra/tree/main/01_Vectors_and_Spaces)
    * [Vectors](https://kkufieta.github.io/linear-algebra/01_Vectors_and_Spaces/01_Vectors.html)
    * [Linear combinations and spans](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/02_Linear_combinations_and_spans.ipynb)
    * [Linear dependence and independence](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/03_Linear_dependence_and_independence.ipynb)
    * [Subspaces and the basis for a subspace](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/04_Subspaces_and_the_basis_for_a_subspace.ipynb)
    * [Vector dot and cross products](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/05_Vector_dot_and_cross_products.ipynb)
    * [Matrices for solving systems by elimination](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/06_Matrices_for_solving_systems_by_elimination.ipynb)
    * [Null space and column space](https://github.com/kkufieta/linear-algebra/blob/main/01_Vectors_and_Spaces/07_Null_space_and_column_space.ipynb)
2. [Matrix transformations](https://github.com/kkufieta/linear-algebra/tree/main/02_Matrix_Transformations)
    * Functions and linear transformations
    * Linear transformation examples
    * Transformations and matrix multiplication
    * Inverse functions and transformations
    * Finding inverses and determinants
    * More determinant depth
    * Transpose of a matrix
3. [Alternate coordinate systems (bases)](https://github.com/kkufieta/linear-algebra/tree/main/03_Alternate_Coordinate_Systems)
    * Orthogonal complements
    * Orthogonal projections
    * Change of basis
    * Orthonormal bases and the Gram-Schmidt process
    * Eigen-everything
    
    
### Rendering Jupyter Notebooks on Github
Jupyter notebooks (especially latex math equations) don't render well on Github. They do also often tend to take a long time to load, and half of the time fail to load properly.

To get better and faster results and all your math rendered, convert the notebook as described [here](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/working-with-jupyter-notebook-files-on-github) into an HTML file using this command:
```bash
$ jupyter nbconvert --to html NOTEBOOK-NAME.ipynb
```

### Source
[Linear Algebra @Khanacademy](https://www.khanacademy.org/math/linear-algebra)
