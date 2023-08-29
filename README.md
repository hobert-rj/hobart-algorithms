# Algorithms README

Welcome to this tutorial! This README will guide you through setting up a Conda environment, installing Python and Jupyter Notebook, and using the `environment.yml` file to manage your environment.

## Install tools

Install mini conda from [mini-conda](https://docs.conda.io/en/latest/miniconda.html)

## 1. Clone

Clone this project from GitHub:
```bash
git clone https://github.com/hobert-rj/hobart-algorithms.git
```

## 2. Environment Setup

Create and install environment:

```bash
conda env create --file environment.yml
```

Or to create an environment in your active directory:

```bash
conda env create --prefix ./env --file environment.yml
```

## 3. Start

Whenever you want to work on your project, activate the environment.:

```bash
conda activate hobart_algorithms
```

Or to run the environment installed in your active directory:

```bash
conda activate ./env
```

While your environment is active, start Jupyter Notebook to work on your notebooks:

```bash
jupyter notebook
```

<br>
Created by Hossein Rajabi
