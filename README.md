# Numerical-study-of-simple-inflationary-models

This repository contains the Jupyter notebook developed as part of my final year BSc Physics and Astrophysics research project "Numerical study of simple inflationary models", where I investigated two simple inflationary models in the early universe.

## Project overview

This project numerically investigates two inflationary potentials:

- Quadratic potential 
- Quartic potential

The numerical calculations involves solving the background equations of motion, identifying the end of inflation, and calculating the primordial perturbation observables. The resulting predictions are used to investigate the properties of each model and compare their predictions.

# Repository structure 

```text
├── code/                    
│   └── Numerical study of simple inflationary models/              
│       ├── Inflationary models.ipynb     
│       ├── Observational comparison.ipynb 
│       └── *.pdf            
└── README.md                                              
```

- ```Inflationary models.ipynb ```: Implementation of the quadratic and quartic inflationary models, including numerical solutions and calculations of inflationary obseravbles.
- ```Observational comparison.ipynb ```: Comparison of model predictions with observable constraints, using external code and publicly available MCMC chain data.
- ```*.pdf ```: PDF files containing plots generated from the numerical modelling and observational comparison.
- ```README.md ```: Project overview, notebook descriptions and acknowledgment.

### Note these scripts require the following tools and libraries:

```
- jupyter 
- numpy
- matplotlib
- scipy
- seaborn
- getdist
```



# External code and Data

The observational comparison section of this project uses plotting framework and data accompanying [Balkenhol et al. 2025](https://arxiv.org/abs/2512.10613), Inflation at the End of 2025: Constraints on r and ns Using the Latest CMB and BAO Data. 

- [Original code and data repository](https://github.com/Lbalkenhol/r_ns_2025)

The original SPA_BK and SPA_BK_DESI chains are not included in this repository, users should obtain them from the original source and follow its reuse terms.

# Acknowledgement

I would like to thank my project supervisor, David Seery at the University of Sussex for his guidance and supervision throughout this research project.

I also acknowledge [Balkenhol et al. 2025](https://arxiv.org/abs/2512.10613) for making their research, observational data and associated computational resources publicly available, which supported the observational comparison section of this project.






