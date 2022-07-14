# Probabilistic Programming  and Bayesian Computing with PyMC

Material for course on Bayesian Computation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fonnesbeck/bayes_course_2022/master) 

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/products/individual#download-section) (Python 3.10) setup and installed on your system. If you do not, please download and install Anaconda on your system before proceeding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/bayes_course_2022.git

otherwise you can [download a zip file](https://github.com/fonnesbeck/bayes_course_2022/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create

from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate bayes_course

Then, you can start **JupyterLab** to access the materials:

    jupyter lab

The binder link above should also provide a working environment.

## Pre-course Work

In advance of the course, we would like attendees to complete a short homework notebook that will ensure everyone has the requisite baseline knowledge. You can find this Jupyter notebook in the `/notebooks` subdirectory (under `Section0-Pre_Work.ipynb`). There is no need to hand this in to anyone, but please reach out if you have difficulty with any of the problems (or with setting up your computing environment) by creating an [issue](https://github.com/fonnesbeck/bayes_course_2022/issues) in this repository, or by emailing.

## Course Outline

The course comprises four 3-hour modules of videoconference lectures, along with short associated hands-on projects to reinforce materials covered during lectures. The sections cover core materials related to Bayesian computation using PyMC, and include:

### Monday, July 25

**Bayesian Hierarchical Models** 09:30 – 13:30 ET / 15:30-19:30 CET
- The anatomy of a Bayesian model
- The PyMC API
- Motivation and case studies
- Partial pooling
- Building hierarchical models
- Parameterizations

### Wednesday, July 26

**Markov chain Monte Carlo** 09:30 – 13:30 ET / 15:30-19:30 CET
- Probability density functions, inverse CDF sampling
- Rejection sampling
- MCMC basics
- Metropolis-Hastings samplers
- Gibbs samplers

### Friday, July 27

**Gradient-based MCMC** 09:30 – 13:30 ET / 15:30-19:30 CET
- Problems with first-generation MCMC methods
- Using gradient information to improve MCMC
- Hamiltonian Monte Carlo
- NUTS
- Convergence diagnostics
- Goodness-of-fit checks


### Monday, July 28

**The Bayesian Workflow** 09:30 – 13:30 ET / 15:30-19:30 CET
- Prior predictive checks
- Iterating models
- Posterior predictive checks
- Using the model
