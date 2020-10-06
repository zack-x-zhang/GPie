# GPie
**G**aussian **P**rocess t**i**ny **e**xplorer (work in progress)


features

- simple: an intuitive syntax that imitates scikit-learn
- minimal: a compact core of expressive abstractions
- extensible: a modular design for effortless composition


functionalities

- kernel functions
    - white kernel
    - constant kernel
    - radial basis function kernel
    - rational quadratic kernel
    - Matérn kernel
    - Ornstein–Uhlenbeck kernel
    - periodic kernel
    - spectral kernel
    - neural kernel
- kernel operators
    - elementwise sum
    - elementwise product
    - elementwise exponentiation
    - Kronecker sum (in progress)
    - Kronecker product (in progress)
- Gaussian process regressor
- Gaussian process classifier (in progress)
- t process regressor (in progress)
- t process classifier (in progress)
- Bayesian optimizer


computational backend

- linear algebra: numpy
- optimization: scipy
- sampling inference: pymc3 (in progress)