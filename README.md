# Bayesian Optimization applied to the magnesioreduction of intermetallics

This repository accompanies the article:

**"Bayesian Optimization of the experimental parameters of complex material synthesis: application to the magnesioreduction of rare-earth free (Mn<sub>1</sub>Fe<sub>1−x</sub>)<sub>5</sub>Si<sub>3</sub> magnetocaloric"**

---

## Overview

This project demonstrates the application of Bayesian Optimization (BO) to efficiently explore and optimize the multi-parameter synthesis space of the (Mn<sub>1</sub>Fe<sub>1−x</sub>)<sub>5</sub>Si<sub>3</sub> magnetocaloric material via **magnesioreduction**. 

The goal is to maximize the **phase purity** of the target compound using minimal experimental trials through an active learning loop. The notebook includes:

- Definition of the parameter space (7 experimental variables)
- Surrogate model construction (Gaussian Process)
- Acquisition strategy
- Visualization and interpretation of BO results

---

## Repository Structure

```
BO_Magnesioreduction_MnFeSi_Magnetocaloric/
├── notebooks/
│   └── BO_Magnesioreduction_LeTonquesse.ipynb                                   
├── env/
│   └── BO_env.yml
├── LICENSE
├── .gitignore
└── README.md
```

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/SLTCrismat/BO_Magnesioreduction_MnFeSi_Magnetocaloric.git
cd your-repo
```

### 2. Create and activate the Conda environment

```bash
conda env create -f BO_env.yml
conda activate BO_env
```

### 3. Launch the notebook

```bash
jupyter notebook notebooks/BO_Magnesioreduction_LeTonquesse.ipynb
```

---

## Requirements

The Conda environment handles dependencies. Main packages include:

- `numpy`, `pandas`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `GPyOpt` or `BoTorch` (depending on your implementation)
- `jupyter`

---

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

---

## Contact

For questions, please contact: Sylvain Le Tonquesse (CNRS, CRISMAT laboratory, Caen, France) – *sylvain.letonquesse@cnrs.fr*

---

## Citation

---
