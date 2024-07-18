# LOO-CV Tutorial

This repository contains a Jupyter notebook tutorial demonstrating how to carry out leave-one-out cross-validation (LOO-CV) using the Pareto-smoothed importance sampling (PSIS) approximation. The tutorial uses a synthetic dataset example from Welbanks et al. 2023 and the `arviz` package [(link)](https://python.arviz.org/en/stable/).

## Overview

In this tutorial, you will learn how to:
- Perform LOO-CV using PSIS.
- Use the `arviz` package for LOO-CV.
- Apply these techniques to exoplanet atmospheric analysis using synthetic data.

## Tutorial Content

The main steps covered in the notebook include:
1. **Introduction to LOO-CV**: An overview of the method and its applications.
2. **Required Packages**: Importing necessary libraries including `numpy`, `matplotlib`, `arviz`, and `spectres`.
3. **Generating Pointwise Log Likelihood**: Instructions on how to generate the required data for LOO-CV.
4. **Performing LOO-CV**: Detailed steps to carry out LOO-CV using the provided dataset.
5. **Analysis and Visualization**: Techniques to analyze and visualize the results.

## Citation

If you find this tutorial helpful, please consider citing the following papers:

1. Welbanks et al. 2023, *On the Application of Bayesian Leave-one-out Cross-validation to Exoplanet Atmospheric Analysis*. [Link](https://ui.adsabs.harvard.edu/abs/2023AJ....165..112W/abstract)

2. McGill et al. 2023, *First semi-empirical test of the white dwarf mass-radius relationship using a single white dwarf via astrometric microlensing*. [Link](https://ui.adsabs.harvard.edu/abs/2023MNRAS.520..259M/abstract)

3. Nixon et al. 2024, *Methods for Incorporating Model Uncertainty into Exoplanet Atmospheric Analysis*. [Link](https://ui.adsabs.harvard.edu/abs/2024ApJ...966..156N/abstract)

## Getting Started

### Prerequisites

Ensure you have the following packages installed:
- `numpy`
- `matplotlib`
- `arviz`
- `spectres`

You can install them using pip:
```bash
pip install numpy matplotlib arviz spectres
```

### Running the Tutorial

1. Clone the repository:
```bash
git clone https://github.com/your-username/loocv_tutorial.git
```

2. Navigate to the repository directory:
```bash
cd loocv_tutorial
```

3. Open the Jupyter notebook:
```bash
jupyter notebook loocv_tutorial.ipynb
```

4. Follow the steps in the notebook to perform LOO-CV on the provided synthetic dataset.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
